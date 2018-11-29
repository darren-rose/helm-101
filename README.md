### helm 101

deploys slack-netes

update the slack token in values.yaml or use --set

```
helm install --set slackbot.token=your-token   ../helm-10
```