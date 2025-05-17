1.Install Python 3.10+ (verify with python --version).\

2.Create a virtual environment:
 python -m venv env
source env/bin/activate       # macOS/Linux
env\\Scripts\\activate      # Windows

3.Upgrade pip & install Django:
pip install --upgrade pip
pip install Django==4.2 

4.Freeze dependencies:
pip freeze > requirements.txt
git add requirements.txt
git commit -m "chore: add project dependencies"
git push
