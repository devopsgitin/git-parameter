pipeline {
  agent any
//   parameters {
//     gitParameter branchFilter: 'origin/(.*)', 
//                  defaultValue: 'feature1', 
//                  name: 'branchname',  
//                  type: 'GitParameterDefinition'
//   }
  stages {
    stage('Example') {
      steps {
//         git branch: "${params.branchname}", 
//             url: 'https://github.com/devopsgitin/git-parameter.git'
        sh 'cat code.txt'
      }
    }
  }
}
