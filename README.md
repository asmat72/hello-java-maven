# hello-java-maven
- 🧪 Simple Java Maven build job for Jenkins CI/CD
- 🛠 Objective:
  - Clone the repository:  
     "git clone "https://github.com/asmat72/my-github-pages-site.git""
  - This project demonstrates how to use **Jenkins** to build a simple **Java HelloWorld application** using **Maven**. It serves as an introductory exercise in CI/CD automation.
- 🧰 Tools Required:
  - All tools used are free and open-source:
     - "Jenkins" (installed locally or via Docker)
     - "Java JDK" (version 8 or 11)
     - "Apache Maven"
     - "Git" (optional — can run from local folder)
- 📂 Deliverables:
     - ✅ A basic Java HelloWorld app (`HelloWorld.java`)
     - ✅ A valid `pom.xml` for Maven build configuration
     - ✅ Jenkins Freestyle job configured to build the app
     - ✅ Screenshot of successful Jenkins build console output
- 📦 Repository Structure:
      - hello-java-maven/
        - ├── src/
           - │ └── main/
                - │ └── java/
                     - │ └── HelloWorld.java //
        - ├── pom.xml
        - └── README.md
        - (main): hello-java-maven  pom.xml  README.md
- 🧭 Step-by-Step Guide:
  - 1️⃣ Create the Java App:
      - Create the file `src/main/java/HelloWorld.java`
  - 2️⃣ Create the Maven Configuration File:
      - Create a "pom.xml" in the root directory.
  - 3️⃣ Start Jenkins (Using Docker Or AWS Instances (Public IP)):
      - If Jenkins is not installed locally, run:
        - Then open http://<your-public-IP>:8080 in your browser.
  - 4️⃣ Configure Maven in Jenkins:
      - Set up Apache Maven in Jenkins for building Java projects.
      -  Steps:
           1. "Access Jenkins Configuration"
           2. "Add Maven"
           3. "Manual Installation"
           4. "Save Configuration"
           5. "Result"
               - Maven is now configured and ready to use in Jenkins build jobs.
  - 5️⃣ Create Jenkins Freestyle Job:
      - Set up a Jenkins Freestyle project to automate builds for a Java Maven application.
      - Steps:
           1. "Access Jenkins Dashboard"
           2. "Create New Job"
           3. "Configure the Job"
           4. "Save and Build"
           5. "Result"
               - Jenkins will execute the Maven build and display logs under "Build History" → "Console Output".
  - 6️⃣ Configure the Build:
      - Set up build steps in a Jenkins Freestyle project to compile and package a Java Maven application.
      - Steps:
           1. "Open Your Jenkins Job"
           2. "Add Build Step"
           3. "Configure Maven Build"
           4. "Save Configuration"
           5. "Result"
               - Jenkins will run the Maven build during each job execution, compiling and packaging your Java project.
  - 7️⃣ Run the Build:
      - Console output you should see: "BUILD SUCCESS"
  - ✅ Summary:
      - This project successfully demonstrates.
      - Creating a Java Maven project.
      - Automating the build process using Jenkins.
      - Understanding basic CI/CD pipeline setup.
