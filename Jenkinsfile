// pipeline {
//     agent any
//     stages {
//         stage('Hello') {
//             steps {
//                 echo "hello from jenkisnfile second try and more"
//             }
//         }
//         stage('for the fix branch') {
//             when {
//                     branch "fix-*"
//             }
//             steps {
//                 echo '''
//                 cat README.md
//                 '''
//             }
//         }
//         stage('for the PR') {
//             when  {
//                 branch 'PR-*'
//             }
//             steps {
//                 echo 'this only runs for the PRs'
//             }
//         }
//     }
// }

@Library('utils') _

log.info 'Starting'
log.warning 'Nothing to do!'