pipeline {
agent any
options {
skipStagesAfterUnstable()
}
stages {
stage('Build') {
steps {
echo 'Building Noman'
}
}
stage('Test') {
steps {
echo 'Testing Noman'
}
}
stage('Deploy') {
steps {
echo 'Deploying Noman'
}
}
}
}
