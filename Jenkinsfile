
node {
    stage (checkout){
      git "https://github.com/chaitukr111/terraform-aws-jenkins.git"
      sh "pwd;ls"
      shortCommit = sh(returnStdout: true, script: "git log").trim()
    }
}
