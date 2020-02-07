pipeline {
agent {
  label 'master'
}
stages {
stage('test stage for jenkinsfile'){
steps{
echo 'hello world'
}
}
stage('stage 2'){
  when {
   branch 'feature/*'
  }
steps{
echo 'only when feature'
}
}
}
}
