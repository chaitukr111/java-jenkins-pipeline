
node {
    sh "pwd;ls"
    shortCommit = sh(returnStdout: true, script: "git log -n 1 --pretty=format:'%h'").trim()
}
