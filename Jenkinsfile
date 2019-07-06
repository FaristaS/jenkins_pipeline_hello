node {
    stage('build'){
        echo "building"
    }
}
node {
    stage('test'){
        echo "testing"
    }
}
stage('Get approval'){
    input "Deploy to qa?"
}
node {
    stage('deploy to qa'){
        echo "deploying"
    }
}
stage('Get approval'){
    input "Deploy to PROD?"
}
node {
    stage('deploy to PROD'){
        echo "deploying to PROD"
    }
}
