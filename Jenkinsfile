
@Library("jenkins-shared-library") _

def cdConfig = [
    chart: [
        repo: "https://github.com/dhavlev/helm-charts.git",
        branch: "voting-app"
    ],
    infra: [
        chart: "voting-app-redis"
    ]
]


facade{    
    cd = cdConfig
}