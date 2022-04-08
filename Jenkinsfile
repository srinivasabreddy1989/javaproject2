node {
    stage('Preparation') {
        checkout scm
    }
    stage('Who am i?') {
        echo "This job was triggered by a  and jenkins bothGit push to branch: ${env.BRANCH_NAME}"
    }
}