pipeline{
    agent{
        label{
            label "slave-2"
            customWorkspace "/mnt/slave-2 "
        }
    }
    stages{
        stage("one"){
            steps{
                echo "This is Master Branch"
            }
        }
    }
}
