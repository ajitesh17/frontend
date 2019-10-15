node('master'){
   stage('git checkout'){
                  git 'https://github.com/ajitesh17/hclhackathon'
              }
   stage('angular build'){
             sh 'npm build'
             sh 'npm install'
             sh 'ng build'
         }
}
