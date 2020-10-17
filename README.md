# Declarative-Pipeline

here stage git checkout taken from pipeline synatx select git and genearte pipeline and put code in stage
It generate as below
git 'https://github.com/adukdp/hello-world'
put in code
as
==================================================================================================================
pipeline{
    agent any
    stages{
        stage("WELCOME") {
            steps{
                git 'https://github.com/adukdp/hello-world'
            }
            
        }

    }

}
