#!/usr/bin/env groovy

node() {
    step("Build Image") {
        sh('arm build')
    }
    step("Push Image") {
        sh('arm push')
    }
}