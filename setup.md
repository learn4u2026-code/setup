nstall UV (if not installed)
pip install uv
if you are using MAC: pip3 install uv
🔹 Check UV installed.
uv --version
🔹 Check Installed Packages
optional  command: uv pip list
🔹 Check Available Python Versions
uv python list
Specific version:
if you wanted to install any specific version of the python using the uv then 
use the below command:
uv python install <mention the cpython interpreter version>
🔹 Create Virtual Environment
uv venv <your-env-name> --python <your-python-version>
From requirements file:
1
Class-02-28-Mar-Intro-GenAI-Tools-UV-Setup-Course-Access-&-Resources-Guide-Git-&-Github-Setup-Guide-by-Sunny
uv pip install -r requirements.txt
