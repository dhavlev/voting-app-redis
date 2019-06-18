
@Library("jenkins-shared-library") _

def cdConfig = [
    chart: [
        repo: "https://github.com/dhavlev/helm-charts.git",
        branch: "voting-app"
    ]
]

def ciConfig = [
    dockerRegistry: "dhavlev",
    repoName: "voting-app-redis",
    version: "1.0.0"
]


facade{    
    cd = cdConfig
}