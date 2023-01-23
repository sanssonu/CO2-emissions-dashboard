# CO2-emissions-dashboard
Interactive visualization dashboard on CO2 emissions in Python with Panel <br>

<p>Here are the steps to run this project:</p>
<ol>
<li>Create a project folder. Go into this folder and open command prompt.</li><br>

<li>Create a virtual environment for this project.</li>
<ul>
  <li>For Windows:</li>
  
        python -m venv path\to\myenv
        cd path\to\myenv
        Scripts\activate.bat
  ![cmd1](https://github.com/sanssonu/CO2-emissions-dashboard/tree/main/images/cmd-01.png)
  <li>For Mac:</li>
    
        python3 -m venv ./
        source bin/activate
</ul>
<p>This will create an isolated environment for our Python project so that this project can have its own dependencies and packages, regardless of whatever dependencies every other project has.</p>
<li>
Install hvplot and Jupyter Lab with:<br>

        pip3 install hvplot jupyterlab
<p>Now, go out of the virtual environment with:</p>

        deactivate
<p>We'll now install panel in the base environment instead of our virtual environment, otherwise the plots might not be interactive in Jupyter Lab.</p>

        pip3 install panel
</li>
<li><p>Go back to the virtual environment and open jupyter lab with:</p>

        source bin/activate
        jupyter lab
<p>
Alternatively, you can clone this repository and copy and paste the files in your own project folder as instructed above.</p>
</li>
</ol>
