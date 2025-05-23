

# GithubComArgoprojArgoEventsPkgApisEventsV1alpha1GitArtifact


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**branch** | **String** |  |  [optional]
**cloneDirectory** | **String** | Directory to clone the repository. We clone complete directory because GitArtifact is not limited to any specific Git service providers. Hence we don&#39;t use any specific git provider client. |  [optional]
**creds** | [**GithubComArgoprojArgoEventsPkgApisEventsV1alpha1GitCreds**](GithubComArgoprojArgoEventsPkgApisEventsV1alpha1GitCreds.md) |  |  [optional]
**filePath** | **String** |  |  [optional]
**insecureIgnoreHostKey** | **Boolean** |  |  [optional]
**ref** | **String** |  |  [optional]
**remote** | [**GithubComArgoprojArgoEventsPkgApisEventsV1alpha1GitRemoteConfig**](GithubComArgoprojArgoEventsPkgApisEventsV1alpha1GitRemoteConfig.md) |  |  [optional]
**sshKeySecret** | [**io.kubernetes.client.openapi.models.V1SecretKeySelector**](io.kubernetes.client.openapi.models.V1SecretKeySelector.md) |  |  [optional]
**tag** | **String** |  |  [optional]
**url** | **String** |  |  [optional]



