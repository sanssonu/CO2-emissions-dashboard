# CO2-emissions-dashboard
Interactive visualization dashboard on CO2 emissions in Python with Panel. <br>
![output](https://user-images.githubusercontent.com/73981055/214110113-9dc2a643-fdc4-4233-81f0-44c8fac8e20e.PNG)

<p>Here are the steps to run this project:</p>
<ol>
<li>Create a project folder. Go into this folder and open command prompt.</li><br>

<li>Create a virtual environment for this project.</li>
<ul>
  <li>For Windows:</li>
  
        python -m venv path\to\myenv
        cd path\to\myenv
        Scripts\activate.bat
  ![cmd-01](https://user-images.githubusercontent.com/73981055/214107241-db2858aa-73f8-42bd-b029-6d27e812214b.PNG)
  <li>For Mac:</li>
    
        python3 -m venv ./
        source bin/activate
</ul>
<p>This will create an isolated environment for our Python project so that this project can have its own dependencies and packages, regardless of whatever dependencies every other project has.</p>
<li>
Install hvplot and Jupyter Lab with:<br>

     pip3 install hvplot jupyterlab
![cmd-02](https://user-images.githubusercontent.com/73981055/214107468-f8134d97-27e4-46bc-a07f-72439d1f29ff.PNG)
<p>Now, go out of the virtual environment with:</p>

        deactivate
 ![cmd-03](https://user-images.githubusercontent.com/73981055/214107618-9fd526d3-0733-417c-8951-53b509b3c0c5.PNG)
<p>We'll now install panel in the base environment instead of our virtual environment, otherwise the plots might not be interactive in Jupyter Lab.</p>

        pip3 install panel
</li>
  
 ![cmd-04](https://user-images.githubusercontent.com/73981055/214107727-b958ef15-b7f2-4616-b4c6-bb521d7d9274.PNG)
<li><p>Go back to the virtual environment and open jupyter lab with:</p>

        source bin/activate.bat
        jupyter lab
 ![cmd-05](https://user-images.githubusercontent.com/73981055/214107922-80642af0-18bd-4dda-a76a-cde3fc952840.PNG)
<p>Alternatively, you can clone this repository and copy and paste the files in your own project folder made above.</p>
</li>
<li><p>To serve the dashboard locally, use the command:</p></li>

        panel serve co2_emissions_dashboard.ipynb
</ol>
