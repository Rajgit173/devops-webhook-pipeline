pipeline {
agent any

stages {
stage('Checkout'){
steps {
echo 'Checking out source code....'
checkout scm
}
}

stage('Build'){
steps {
echo 'Build stage started'
echo 'Application build completed'
}
}

stage('Test'){
steps {
echo 'Running tests...'
echo 'Tests completed successfully'
}
}
stage('Success'){
steps {
echo '========================================='
echo 'CI PIPELINE COMPLETED SUCCESSFULLY'
echo '_________________________________________'
}
}
}
}
