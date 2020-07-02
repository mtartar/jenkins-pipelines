# Jenkins pipelines

## Pipeline

[pipeline](https://www.jenkins.io/doc/book/pipeline)

[declarative pipeline](https://www.jenkins.io/doc/book/pipeline/syntax/#declarative-pipeline) uses DSL

[fundamentals](https://www.jenkins.io/doc/book/pipeline/#declarative-pipeline-fundamentals)

[scripted pipeline](https://www.jenkins.io/doc/book/pipeline/syntax/#scripted-pipeline) uses Groovy

[fundamentals](https://www.jenkins.io/doc/book/pipeline/#scripted-pipeline-fundamentals)


[Jenkinsfile](https://www.jenkins.io/doc/book/pipeline/jenkinsfile)



[Glossary](https://www.jenkins.io/doc/book/glossary)

### Blue Ocean

[Create a pipeline](https://jenkins.io/doc/tutorials/create-a-pipeline-in-blue-ocean/)

[pipeline editor](https://jenkins.io/doc/book/blueocean/pipeline-editor/)

[Getting started](https://jenkins.io/doc/book/blueocean/getting-started/)


### Flow control

[flow control](https://www.jenkins.io/doc/book/pipeline/syntax/#flow-control)


### Stashing files


### Docker

https://www.jenkins.io/doc/book/pipeline/docker/


- []()

## Syntax

- [agent](https://www.jenkins.io/doc/book/pipeline/syntax/#agent)

- [archive](https://www.jenkins.io/doc/pipeline/steps/workflow-basic-steps/#archive-archive-artifacts)

- [bat](https://www.jenkins.io/doc/pipeline/steps/workflow-durable-task-step/#bat-windows-batch-script)

- [build](https://www.jenkins.io/doc/pipeline/steps/pipeline-build-step/#build-build-a-job)

- [catchError](https://www.jenkins.io/doc/pipeline/steps/workflow-basic-steps/#dir-change-current-directory)

- [checkout](https://www.jenkins.io/doc/pipeline/steps/workflow-scm-step/#checkout-general-scm)

- [deleteDir](https://www.jenkins.io/doc/pipeline/steps/workflow-basic-steps/#deletedir-recursively-delete-the-current-directory-from-the-workspace)

- [dir](https://www.jenkins.io/doc/pipeline/steps/workflow-basic-steps/#dir-change-current-directory)

- [echo](https://www.jenkins.io/doc/pipeline/steps/workflow-basic-steps/#echo-print-message)

- [error](https://www.jenkins.io/doc/pipeline/steps/workflow-basic-steps/#error-error-signal)

- [emailext](https://www.jenkins.io/doc/pipeline/steps/email-ext/#emailext-extended-email)

- [emailextrecipients](https://www.jenkins.io/doc/pipeline/steps/email-ext/#emailextrecipients-extended-email-recipients)

- [environment](https://www.jenkins.io/doc/book/pipeline/syntax/#environment)

- [fileExists](https://www.jenkins.io/doc/pipeline/steps/workflow-basic-steps/#fileexists-verify-if-file-exists-in-workspace)

- [getContext](https://www.jenkins.io/doc/pipeline/steps/workflow-basic-steps/#archive-archive-artifacts)

- [input](https://www.jenkins.io/doc/book/pipeline/syntax/#input)

- [isUnix](https://www.jenkins.io/doc/pipeline/steps/workflow-basic-steps/#isunix-checks-if-running-on-a-unix-like-node)

- [junit]()

- [load](https://www.jenkins.io/doc/pipeline/steps/workflow-cps/#load-evaluate-a-groovy-source-file-into-the-pipeline-script)

- [mail](https://www.jenkins.io/doc/pipeline/steps/workflow-basic-steps/#mail-mail)

- [node](https://www.jenkins.io/doc/book/pipeline/#node) and [node](https://www.jenkins.io/doc/pipeline/steps/workflow-durable-task-step/#bat-windows-batch-script)

- [options](https://www.jenkins.io/doc/book/pipeline/syntax/#options)

- [parallel](https://www.jenkins.io/doc/pipeline/steps/workflow-cps/#parallel-execute-in-parallel)

- [parameters](https://www.jenkins.io/doc/book/pipeline/syntax/#parameters)

- [pipeline](https://www.jenkins.io/doc/book/pipeline/#pipeline)

- [post](https://www.jenkins.io/doc/book/pipeline/syntax/#post)

- [powershell](https://www.jenkins.io/doc/pipeline/steps/workflow-durable-task-step/#bat-windows-batch-script)

- [pwd](https://www.jenkins.io/doc/pipeline/steps/workflow-basic-steps/#fileexists-verify-if-file-exists-in-workspace)

- [pwsh](https://www.jenkins.io/doc/pipeline/steps/workflow-durable-task-step/#pwsh-powershell-core-script)

- [readFile](https://www.jenkins.io/doc/pipeline/steps/workflow-basic-steps/#fileexists-verify-if-file-exists-in-workspace)

- [retry](https://www.jenkins.io/doc/pipeline/steps/workflow-basic-steps/#retry-retry-the-body-up-to-n-times)

- [scm]()

- [script](https://www.jenkins.io/doc/book/pipeline/syntax/#script)

- [sh](https://www.jenkins.io/doc/pipeline/steps/workflow-durable-task-step/#sh-shell-script)

```
sh 'make check || true'
```

value zero => continue
value non-zero => exit


- [sleep](https://www.jenkins.io/doc/pipeline/steps/workflow-basic-steps/#fileexists-verify-if-file-exists-in-workspace)

- [stage](https://www.jenkins.io/doc/book/pipeline/syntax/#stage)

- [stages](https://www.jenkins.io/doc/book/pipeline/syntax/#stages)

- [stash](https://www.jenkins.io/doc/pipeline/steps/workflow-basic-steps/#fileexists-verify-if-file-exists-in-workspace)

- [steps](https://www.jenkins.io/doc/book/pipeline/syntax/#steps)

- [step](https://www.jenkins.io/doc/book/pipeline/#step)

- [timeout](https://www.jenkins.io/doc/pipeline/steps/workflow-basic-steps/#fileexists-verify-if-file-exists-in-workspace)

- [tools](https://www.jenkins.io/doc/book/pipeline/syntax/#tools)

- [tool](https://www.jenkins.io/doc/pipeline/steps/workflow-basic-steps/#tool-use-a-tool-from-a-predefined-tool-installation)

- [triggers](https://www.jenkins.io/doc/book/pipeline/syntax/#triggers)

- [unarchive](https://www.jenkins.io/doc/pipeline/steps/workflow-basic-steps/#unarchive-copy-archived-artifacts-into-the-workspace)

- [unstable](https://www.jenkins.io/doc/pipeline/steps/workflow-basic-steps/#tool-use-a-tool-from-a-predefined-tool-installation)

- [unstash](https://www.jenkins.io/doc/pipeline/steps/workflow-basic-steps/#tool-use-a-tool-from-a-predefined-tool-installation)

- [waitUntil](https://www.jenkins.io/doc/pipeline/steps/workflow-basic-steps/#waituntil-wait-for-condition)

- [warnError](https://www.jenkins.io/doc/pipeline/steps/workflow-basic-steps/#warnerror-catch-error-and-set-build-and-stage-result-to-unstable)

- [when](https://www.jenkins.io/doc/book/pipeline/syntax/#when)

- [withContext](https://www.jenkins.io/doc/pipeline/steps/workflow-basic-steps/#withcontext-use-contextual-object-from-internal-apis-within-a-block)

- [withEnv](https://www.jenkins.io/doc/pipeline/steps/workflow-basic-steps/#withenv-set-environment-variables)

- [wrap](https://www.jenkins.io/doc/pipeline/steps/workflow-basic-steps/#warnerror-catch-error-and-set-build-and-stage-result-to-unstable)

- [writeFile](https://www.jenkins.io/doc/pipeline/steps/workflow-basic-steps/#writefile-write-file-to-workspace)

- [ws](https://www.jenkins.io/doc/pipeline/steps/workflow-durable-task-step/#ws-allocate-workspace)


## Misc.

- [cron syntax](https://www.jenkins.io/doc/book/pipeline/syntax/#cron-syntax)

