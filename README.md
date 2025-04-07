End to End machine learning project day to day
conda create -p venv python==3.8 -y
CALL conda.bat activate
conda activate venv/
pip install -r requirements.txt
<<<<<<< HEAD

git add .
git commit -m "Initial commit"
git push
=======

FROM python: 3.8-alpine
COPY . /applicati
WORKDIR /application
RUN pip install -r requirements.txt
CMD python application.py

docker build -t student_grade .

Checking it

>>>>>>> 46e039d2588e615ea9565d42d05571dcf4e08c8a
