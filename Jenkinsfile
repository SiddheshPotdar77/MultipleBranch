@Library('library')_
pipeline
{
    agent any
    stages
    {
        stage('Continous Downlod')
        {
            steps
            {
                script
                {
                    cicd.download("maven")
                }
            }
        }
        stage('Continous Build')
        {
            steps
            {
                script
                {
                    cicd.build()
                }
            }
        }
    }
}



