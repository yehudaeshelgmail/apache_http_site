pipeline {
node ('master'){
    stage 'Checkout'
    checkout scm
    stage "Build Pex"
    sh 'df -k > /tmp/dg.log'
}
}
