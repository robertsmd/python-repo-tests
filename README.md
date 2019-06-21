# python-repo-tests
git ci setup for python repositories

```bash
wget https://raw.githubusercontent.com/robertsmd/python-repo-tests/master/.gitlab-ci.yml
wget https://raw.githubusercontent.com/robertsmd/python-repo-tests/master/.gitignore
wget https://raw.githubusercontent.com/robertsmd/python-repo-tests/master/run_tests.sh
mkdir requirements
cd requirements
wget https://raw.githubusercontent.com/robertsmd/python-repo-tests/master/requirements/testing-requirements.txt
wget https://raw.githubusercontent.com/robertsmd/python-repo-tests/master/requirements/requirements.txt
cd ..

git add .gitignore .gitlab-ci.yml requirements run_tests.sh
```
