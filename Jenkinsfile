pipeline{
  tools
  {
    gradle 'Gradle'
    jdk 'JDK'
  }
  stages
  {
    stage('checkout')
    {
      steps
      {
        git branch:'master', url:'https://github.com/vinayGowda173/gradlejenkins.git'
      }
    }
    stage('build')
    {
     steps
      {
        sh 'gradle build'
      }
    }
    stage('run')
    {
      steps
      {
        sh 'gradle run'
      }
    }
  }
}

  
