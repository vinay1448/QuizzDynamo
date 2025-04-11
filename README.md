# QuizzDynamo

An entertaining, educational quiz like system for individual students to earn rewards through a textual-based multiple choice format.

This is a video presentation on the QuizzDynamo Web Application chiefly facilitating 'quizzes' for students corresponding to their degree('Bachelor's', 'Master's', 'PGDiploma'). Administrators can upload a quiz based on the specific subject, where the questions / options are rendered in the quiz page and answers displayed via a QuizSubmission page.

# QuizzDynamo - AWS CI/CD Deployment

This repository demonstrates a full CI/CD pipeline setup for a Django-based application using AWS services, GitHub, and various DevOps tools.

---

## 🌐 Live URL

**Application**: [x23203595QuizzApp](http://x23203595Quizzapp-env.eba-fp6mvn2f.eu-west-1.elasticbeanstalk.com)

---

## 🧰 Tools & Cloud Services

- **AWS EC2 Instance**
- **AWS Cloud9**
- **AWS CodePipeline**
- **AWS CodeBuild**
- **AWS CloudWatch**
- **AWS Elastic Beanstalk**
- **GitHub**
- **SonarCloud**
- **Pylint**

---

## ⚙️ CI/CD Breakdown

### 🔹 Source Stage

- **Source**: GitHub
- **Repository**: [`x23203595/QuizzDynamo`](https://github.com/x23203595/QuizzDynamo)

---

### 🔹 Build Stage

- **Build Tool**: AWS CodeBuild
- **Project Name**: `x23203595QuizzBuildNewFinal`
- **OS**: Ubuntu
- **Image**: `aws/codebuild/standard:7.0`
- **Role ARN**: `CodeBuildServiceRole`

#### 🔸 Static Code Analysis

- **Tool**: `Pylint`
- **Version**: 2.17.4

#### 🔸 Security Vulnerability Analysis

- **Tool**: `SonarCloud`
- **Scanner**: `sonar-scanner-3.3.0.1492`

---

### 🔹 Deploy Stage

- **Service**: AWS Elastic Beanstalk
- **Application Name**: `x23203595QuizzBean`
- **Environment Name**: `x23203595Quizzapp-env`

---

### 🔹 CodePipeline

- **Pipeline Name**: `x23203595QuizzPipeline`

---

## 🖥️ Languages & Frameworks

- **Python**: 3.9.16
- **Django**: 4.2.11
- **pip**: 21.3.1

---

## 📊 Monitoring

- **Service**: AWS CloudWatch

---



QuizzDynamo
Student Name : Vinay Sriram Iyer
Student ID : 23203595
Cloud DevOpsSec, MSc in Cloud Computing
National College of Ireland Dublin, IRELAND \
Email: x23203595@student.ncirl.ie  
URL: www.ncirl.ie \
Deployed Application 
URL: http://x23203595Quizzapp-env.eba-fp6mvn2f.eu-west-1.elasticbeanstalk.com

Youtube Link : https://youtu.be/wCIaNsw8heg
