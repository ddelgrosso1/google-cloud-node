[//]: # "This README.md file is auto-generated, all changes to this file will be lost."
[//]: # "To regenerate it, use `python -m synthtool`."
<img src="https://avatars2.githubusercontent.com/u/2810941?v=3&s=96" alt="Google Cloud Platform logo" title="Google Cloud Platform" align="right" height="96" width="96"/>

# [Cloud Logging: Node.js Client](https://github.com/googleapis/google-cloud-node/tree/main/handwritten/logging)

[![release level](https://img.shields.io/badge/release%20level-stable-brightgreen.svg?style=flat)](https://cloud.google.com/terms/launch-stages)
[![npm version](https://img.shields.io/npm/v/@google-cloud/logging.svg)](https://www.npmjs.com/package/@google-cloud/logging)




Cloud Logging Client Library for Node.js


A comprehensive list of changes in each version may be found in
[the CHANGELOG](https://github.com/googleapis/google-cloud-node/tree/main/handwritten/logging/CHANGELOG.md).

* [Cloud Logging Node.js Client API Reference][client-docs]
* [Cloud Logging Documentation][product-docs]
* [github.com/googleapis/google-cloud-node/handwritten/logging](https://github.com/googleapis/google-cloud-node/tree/main/handwritten/logging)

Read more about the client libraries for Cloud APIs, including the older
Google APIs Client Libraries, in [Client Libraries Explained][explained].

[explained]: https://cloud.google.com/apis/docs/client-libraries-explained

**Table of contents:**


* [Quickstart](#quickstart)
  * [Before you begin](#before-you-begin)
  * [Installing the client library](#installing-the-client-library)

* [Samples](#samples)
* [Versioning](#versioning)
* [Contributing](#contributing)
* [License](#license)

## Quickstart

### Before you begin

1.  [Select or create a Cloud Platform project][projects].
1.  [Enable the Cloud Logging API][enable_api].
1.  [Set up authentication][auth] so you can access the
    API from your local workstation.

### Installing the client library

```bash
npm install @google-cloud/logging
```




## Samples

Samples are in the [`samples/`](https://github.com/googleapis/google-cloud-node/tree/main/handwritten/logging/samples) directory. Each sample's `README.md` has instructions for running its sample.

| Sample                      | Source Code                       | Try it |
| --------------------------- | --------------------------------- | ------ |
| Config_service_v2.copy_log_entries | [source code](https://github.com/googleapis/google-cloud-node/blob/main/handwritten/logging/samples/generated/v2/config_service_v2.copy_log_entries.js) | [![Open in Cloud Shell][shell_img]](https://console.cloud.google.com/cloudshell/open?git_repo=https://github.com/googleapis/google-cloud-node&page=editor&open_in_editor=handwritten/logging/samples/generated/v2/config_service_v2.copy_log_entries.js,handwritten/logging/samples/README.md) |
| Config_service_v2.create_bucket | [source code](https://github.com/googleapis/google-cloud-node/blob/main/handwritten/logging/samples/generated/v2/config_service_v2.create_bucket.js) | [![Open in Cloud Shell][shell_img]](https://console.cloud.google.com/cloudshell/open?git_repo=https://github.com/googleapis/google-cloud-node&page=editor&open_in_editor=handwritten/logging/samples/generated/v2/config_service_v2.create_bucket.js,handwritten/logging/samples/README.md) |
| Config_service_v2.create_bucket_async | [source code](https://github.com/googleapis/google-cloud-node/blob/main/handwritten/logging/samples/generated/v2/config_service_v2.create_bucket_async.js) | [![Open in Cloud Shell][shell_img]](https://console.cloud.google.com/cloudshell/open?git_repo=https://github.com/googleapis/google-cloud-node&page=editor&open_in_editor=handwritten/logging/samples/generated/v2/config_service_v2.create_bucket_async.js,handwritten/logging/samples/README.md) |
| Config_service_v2.create_exclusion | [source code](https://github.com/googleapis/google-cloud-node/blob/main/handwritten/logging/samples/generated/v2/config_service_v2.create_exclusion.js) | [![Open in Cloud Shell][shell_img]](https://console.cloud.google.com/cloudshell/open?git_repo=https://github.com/googleapis/google-cloud-node&page=editor&open_in_editor=handwritten/logging/samples/generated/v2/config_service_v2.create_exclusion.js,handwritten/logging/samples/README.md) |
| Config_service_v2.create_link | [source code](https://github.com/googleapis/google-cloud-node/blob/main/handwritten/logging/samples/generated/v2/config_service_v2.create_link.js) | [![Open in Cloud Shell][shell_img]](https://console.cloud.google.com/cloudshell/open?git_repo=https://github.com/googleapis/google-cloud-node&page=editor&open_in_editor=handwritten/logging/samples/generated/v2/config_service_v2.create_link.js,handwritten/logging/samples/README.md) |
| Config_service_v2.create_sink | [source code](https://github.com/googleapis/google-cloud-node/blob/main/handwritten/logging/samples/generated/v2/config_service_v2.create_sink.js) | [![Open in Cloud Shell][shell_img]](https://console.cloud.google.com/cloudshell/open?git_repo=https://github.com/googleapis/google-cloud-node&page=editor&open_in_editor=handwritten/logging/samples/generated/v2/config_service_v2.create_sink.js,handwritten/logging/samples/README.md) |
| Config_service_v2.create_view | [source code](https://github.com/googleapis/google-cloud-node/blob/main/handwritten/logging/samples/generated/v2/config_service_v2.create_view.js) | [![Open in Cloud Shell][shell_img]](https://console.cloud.google.com/cloudshell/open?git_repo=https://github.com/googleapis/google-cloud-node&page=editor&open_in_editor=handwritten/logging/samples/generated/v2/config_service_v2.create_view.js,handwritten/logging/samples/README.md) |
| Config_service_v2.delete_bucket | [source code](https://github.com/googleapis/google-cloud-node/blob/main/handwritten/logging/samples/generated/v2/config_service_v2.delete_bucket.js) | [![Open in Cloud Shell][shell_img]](https://console.cloud.google.com/cloudshell/open?git_repo=https://github.com/googleapis/google-cloud-node&page=editor&open_in_editor=handwritten/logging/samples/generated/v2/config_service_v2.delete_bucket.js,handwritten/logging/samples/README.md) |
| Config_service_v2.delete_exclusion | [source code](https://github.com/googleapis/google-cloud-node/blob/main/handwritten/logging/samples/generated/v2/config_service_v2.delete_exclusion.js) | [![Open in Cloud Shell][shell_img]](https://console.cloud.google.com/cloudshell/open?git_repo=https://github.com/googleapis/google-cloud-node&page=editor&open_in_editor=handwritten/logging/samples/generated/v2/config_service_v2.delete_exclusion.js,handwritten/logging/samples/README.md) |
| Config_service_v2.delete_link | [source code](https://github.com/googleapis/google-cloud-node/blob/main/handwritten/logging/samples/generated/v2/config_service_v2.delete_link.js) | [![Open in Cloud Shell][shell_img]](https://console.cloud.google.com/cloudshell/open?git_repo=https://github.com/googleapis/google-cloud-node&page=editor&open_in_editor=handwritten/logging/samples/generated/v2/config_service_v2.delete_link.js,handwritten/logging/samples/README.md) |
| Config_service_v2.delete_sink | [source code](https://github.com/googleapis/google-cloud-node/blob/main/handwritten/logging/samples/generated/v2/config_service_v2.delete_sink.js) | [![Open in Cloud Shell][shell_img]](https://console.cloud.google.com/cloudshell/open?git_repo=https://github.com/googleapis/google-cloud-node&page=editor&open_in_editor=handwritten/logging/samples/generated/v2/config_service_v2.delete_sink.js,handwritten/logging/samples/README.md) |
| Config_service_v2.delete_view | [source code](https://github.com/googleapis/google-cloud-node/blob/main/handwritten/logging/samples/generated/v2/config_service_v2.delete_view.js) | [![Open in Cloud Shell][shell_img]](https://console.cloud.google.com/cloudshell/open?git_repo=https://github.com/googleapis/google-cloud-node&page=editor&open_in_editor=handwritten/logging/samples/generated/v2/config_service_v2.delete_view.js,handwritten/logging/samples/README.md) |
| Config_service_v2.get_bucket | [source code](https://github.com/googleapis/google-cloud-node/blob/main/handwritten/logging/samples/generated/v2/config_service_v2.get_bucket.js) | [![Open in Cloud Shell][shell_img]](https://console.cloud.google.com/cloudshell/open?git_repo=https://github.com/googleapis/google-cloud-node&page=editor&open_in_editor=handwritten/logging/samples/generated/v2/config_service_v2.get_bucket.js,handwritten/logging/samples/README.md) |
| Config_service_v2.get_cmek_settings | [source code](https://github.com/googleapis/google-cloud-node/blob/main/handwritten/logging/samples/generated/v2/config_service_v2.get_cmek_settings.js) | [![Open in Cloud Shell][shell_img]](https://console.cloud.google.com/cloudshell/open?git_repo=https://github.com/googleapis/google-cloud-node&page=editor&open_in_editor=handwritten/logging/samples/generated/v2/config_service_v2.get_cmek_settings.js,handwritten/logging/samples/README.md) |
| Config_service_v2.get_exclusion | [source code](https://github.com/googleapis/google-cloud-node/blob/main/handwritten/logging/samples/generated/v2/config_service_v2.get_exclusion.js) | [![Open in Cloud Shell][shell_img]](https://console.cloud.google.com/cloudshell/open?git_repo=https://github.com/googleapis/google-cloud-node&page=editor&open_in_editor=handwritten/logging/samples/generated/v2/config_service_v2.get_exclusion.js,handwritten/logging/samples/README.md) |
| Config_service_v2.get_link | [source code](https://github.com/googleapis/google-cloud-node/blob/main/handwritten/logging/samples/generated/v2/config_service_v2.get_link.js) | [![Open in Cloud Shell][shell_img]](https://console.cloud.google.com/cloudshell/open?git_repo=https://github.com/googleapis/google-cloud-node&page=editor&open_in_editor=handwritten/logging/samples/generated/v2/config_service_v2.get_link.js,handwritten/logging/samples/README.md) |
| Config_service_v2.get_settings | [source code](https://github.com/googleapis/google-cloud-node/blob/main/handwritten/logging/samples/generated/v2/config_service_v2.get_settings.js) | [![Open in Cloud Shell][shell_img]](https://console.cloud.google.com/cloudshell/open?git_repo=https://github.com/googleapis/google-cloud-node&page=editor&open_in_editor=handwritten/logging/samples/generated/v2/config_service_v2.get_settings.js,handwritten/logging/samples/README.md) |
| Config_service_v2.get_sink | [source code](https://github.com/googleapis/google-cloud-node/blob/main/handwritten/logging/samples/generated/v2/config_service_v2.get_sink.js) | [![Open in Cloud Shell][shell_img]](https://console.cloud.google.com/cloudshell/open?git_repo=https://github.com/googleapis/google-cloud-node&page=editor&open_in_editor=handwritten/logging/samples/generated/v2/config_service_v2.get_sink.js,handwritten/logging/samples/README.md) |
| Config_service_v2.get_view | [source code](https://github.com/googleapis/google-cloud-node/blob/main/handwritten/logging/samples/generated/v2/config_service_v2.get_view.js) | [![Open in Cloud Shell][shell_img]](https://console.cloud.google.com/cloudshell/open?git_repo=https://github.com/googleapis/google-cloud-node&page=editor&open_in_editor=handwritten/logging/samples/generated/v2/config_service_v2.get_view.js,handwritten/logging/samples/README.md) |
| Config_service_v2.list_buckets | [source code](https://github.com/googleapis/google-cloud-node/blob/main/handwritten/logging/samples/generated/v2/config_service_v2.list_buckets.js) | [![Open in Cloud Shell][shell_img]](https://console.cloud.google.com/cloudshell/open?git_repo=https://github.com/googleapis/google-cloud-node&page=editor&open_in_editor=handwritten/logging/samples/generated/v2/config_service_v2.list_buckets.js,handwritten/logging/samples/README.md) |
| Config_service_v2.list_exclusions | [source code](https://github.com/googleapis/google-cloud-node/blob/main/handwritten/logging/samples/generated/v2/config_service_v2.list_exclusions.js) | [![Open in Cloud Shell][shell_img]](https://console.cloud.google.com/cloudshell/open?git_repo=https://github.com/googleapis/google-cloud-node&page=editor&open_in_editor=handwritten/logging/samples/generated/v2/config_service_v2.list_exclusions.js,handwritten/logging/samples/README.md) |
| Config_service_v2.list_links | [source code](https://github.com/googleapis/google-cloud-node/blob/main/handwritten/logging/samples/generated/v2/config_service_v2.list_links.js) | [![Open in Cloud Shell][shell_img]](https://console.cloud.google.com/cloudshell/open?git_repo=https://github.com/googleapis/google-cloud-node&page=editor&open_in_editor=handwritten/logging/samples/generated/v2/config_service_v2.list_links.js,handwritten/logging/samples/README.md) |
| Config_service_v2.list_sinks | [source code](https://github.com/googleapis/google-cloud-node/blob/main/handwritten/logging/samples/generated/v2/config_service_v2.list_sinks.js) | [![Open in Cloud Shell][shell_img]](https://console.cloud.google.com/cloudshell/open?git_repo=https://github.com/googleapis/google-cloud-node&page=editor&open_in_editor=handwritten/logging/samples/generated/v2/config_service_v2.list_sinks.js,handwritten/logging/samples/README.md) |
| Config_service_v2.list_views | [source code](https://github.com/googleapis/google-cloud-node/blob/main/handwritten/logging/samples/generated/v2/config_service_v2.list_views.js) | [![Open in Cloud Shell][shell_img]](https://console.cloud.google.com/cloudshell/open?git_repo=https://github.com/googleapis/google-cloud-node&page=editor&open_in_editor=handwritten/logging/samples/generated/v2/config_service_v2.list_views.js,handwritten/logging/samples/README.md) |
| Config_service_v2.undelete_bucket | [source code](https://github.com/googleapis/google-cloud-node/blob/main/handwritten/logging/samples/generated/v2/config_service_v2.undelete_bucket.js) | [![Open in Cloud Shell][shell_img]](https://console.cloud.google.com/cloudshell/open?git_repo=https://github.com/googleapis/google-cloud-node&page=editor&open_in_editor=handwritten/logging/samples/generated/v2/config_service_v2.undelete_bucket.js,handwritten/logging/samples/README.md) |
| Config_service_v2.update_bucket | [source code](https://github.com/googleapis/google-cloud-node/blob/main/handwritten/logging/samples/generated/v2/config_service_v2.update_bucket.js) | [![Open in Cloud Shell][shell_img]](https://console.cloud.google.com/cloudshell/open?git_repo=https://github.com/googleapis/google-cloud-node&page=editor&open_in_editor=handwritten/logging/samples/generated/v2/config_service_v2.update_bucket.js,handwritten/logging/samples/README.md) |
| Config_service_v2.update_bucket_async | [source code](https://github.com/googleapis/google-cloud-node/blob/main/handwritten/logging/samples/generated/v2/config_service_v2.update_bucket_async.js) | [![Open in Cloud Shell][shell_img]](https://console.cloud.google.com/cloudshell/open?git_repo=https://github.com/googleapis/google-cloud-node&page=editor&open_in_editor=handwritten/logging/samples/generated/v2/config_service_v2.update_bucket_async.js,handwritten/logging/samples/README.md) |
| Config_service_v2.update_cmek_settings | [source code](https://github.com/googleapis/google-cloud-node/blob/main/handwritten/logging/samples/generated/v2/config_service_v2.update_cmek_settings.js) | [![Open in Cloud Shell][shell_img]](https://console.cloud.google.com/cloudshell/open?git_repo=https://github.com/googleapis/google-cloud-node&page=editor&open_in_editor=handwritten/logging/samples/generated/v2/config_service_v2.update_cmek_settings.js,handwritten/logging/samples/README.md) |
| Config_service_v2.update_exclusion | [source code](https://github.com/googleapis/google-cloud-node/blob/main/handwritten/logging/samples/generated/v2/config_service_v2.update_exclusion.js) | [![Open in Cloud Shell][shell_img]](https://console.cloud.google.com/cloudshell/open?git_repo=https://github.com/googleapis/google-cloud-node&page=editor&open_in_editor=handwritten/logging/samples/generated/v2/config_service_v2.update_exclusion.js,handwritten/logging/samples/README.md) |
| Config_service_v2.update_settings | [source code](https://github.com/googleapis/google-cloud-node/blob/main/handwritten/logging/samples/generated/v2/config_service_v2.update_settings.js) | [![Open in Cloud Shell][shell_img]](https://console.cloud.google.com/cloudshell/open?git_repo=https://github.com/googleapis/google-cloud-node&page=editor&open_in_editor=handwritten/logging/samples/generated/v2/config_service_v2.update_settings.js,handwritten/logging/samples/README.md) |
| Config_service_v2.update_sink | [source code](https://github.com/googleapis/google-cloud-node/blob/main/handwritten/logging/samples/generated/v2/config_service_v2.update_sink.js) | [![Open in Cloud Shell][shell_img]](https://console.cloud.google.com/cloudshell/open?git_repo=https://github.com/googleapis/google-cloud-node&page=editor&open_in_editor=handwritten/logging/samples/generated/v2/config_service_v2.update_sink.js,handwritten/logging/samples/README.md) |
| Config_service_v2.update_view | [source code](https://github.com/googleapis/google-cloud-node/blob/main/handwritten/logging/samples/generated/v2/config_service_v2.update_view.js) | [![Open in Cloud Shell][shell_img]](https://console.cloud.google.com/cloudshell/open?git_repo=https://github.com/googleapis/google-cloud-node&page=editor&open_in_editor=handwritten/logging/samples/generated/v2/config_service_v2.update_view.js,handwritten/logging/samples/README.md) |
| Logging_service_v2.delete_log | [source code](https://github.com/googleapis/google-cloud-node/blob/main/handwritten/logging/samples/generated/v2/logging_service_v2.delete_log.js) | [![Open in Cloud Shell][shell_img]](https://console.cloud.google.com/cloudshell/open?git_repo=https://github.com/googleapis/google-cloud-node&page=editor&open_in_editor=handwritten/logging/samples/generated/v2/logging_service_v2.delete_log.js,handwritten/logging/samples/README.md) |
| Logging_service_v2.list_log_entries | [source code](https://github.com/googleapis/google-cloud-node/blob/main/handwritten/logging/samples/generated/v2/logging_service_v2.list_log_entries.js) | [![Open in Cloud Shell][shell_img]](https://console.cloud.google.com/cloudshell/open?git_repo=https://github.com/googleapis/google-cloud-node&page=editor&open_in_editor=handwritten/logging/samples/generated/v2/logging_service_v2.list_log_entries.js,handwritten/logging/samples/README.md) |
| Logging_service_v2.list_logs | [source code](https://github.com/googleapis/google-cloud-node/blob/main/handwritten/logging/samples/generated/v2/logging_service_v2.list_logs.js) | [![Open in Cloud Shell][shell_img]](https://console.cloud.google.com/cloudshell/open?git_repo=https://github.com/googleapis/google-cloud-node&page=editor&open_in_editor=handwritten/logging/samples/generated/v2/logging_service_v2.list_logs.js,handwritten/logging/samples/README.md) |
| Logging_service_v2.list_monitored_resource_descriptors | [source code](https://github.com/googleapis/google-cloud-node/blob/main/handwritten/logging/samples/generated/v2/logging_service_v2.list_monitored_resource_descriptors.js) | [![Open in Cloud Shell][shell_img]](https://console.cloud.google.com/cloudshell/open?git_repo=https://github.com/googleapis/google-cloud-node&page=editor&open_in_editor=handwritten/logging/samples/generated/v2/logging_service_v2.list_monitored_resource_descriptors.js,handwritten/logging/samples/README.md) |
| Logging_service_v2.tail_log_entries | [source code](https://github.com/googleapis/google-cloud-node/blob/main/handwritten/logging/samples/generated/v2/logging_service_v2.tail_log_entries.js) | [![Open in Cloud Shell][shell_img]](https://console.cloud.google.com/cloudshell/open?git_repo=https://github.com/googleapis/google-cloud-node&page=editor&open_in_editor=handwritten/logging/samples/generated/v2/logging_service_v2.tail_log_entries.js,handwritten/logging/samples/README.md) |
| Logging_service_v2.write_log_entries | [source code](https://github.com/googleapis/google-cloud-node/blob/main/handwritten/logging/samples/generated/v2/logging_service_v2.write_log_entries.js) | [![Open in Cloud Shell][shell_img]](https://console.cloud.google.com/cloudshell/open?git_repo=https://github.com/googleapis/google-cloud-node&page=editor&open_in_editor=handwritten/logging/samples/generated/v2/logging_service_v2.write_log_entries.js,handwritten/logging/samples/README.md) |
| Metrics_service_v2.create_log_metric | [source code](https://github.com/googleapis/google-cloud-node/blob/main/handwritten/logging/samples/generated/v2/metrics_service_v2.create_log_metric.js) | [![Open in Cloud Shell][shell_img]](https://console.cloud.google.com/cloudshell/open?git_repo=https://github.com/googleapis/google-cloud-node&page=editor&open_in_editor=handwritten/logging/samples/generated/v2/metrics_service_v2.create_log_metric.js,handwritten/logging/samples/README.md) |
| Metrics_service_v2.delete_log_metric | [source code](https://github.com/googleapis/google-cloud-node/blob/main/handwritten/logging/samples/generated/v2/metrics_service_v2.delete_log_metric.js) | [![Open in Cloud Shell][shell_img]](https://console.cloud.google.com/cloudshell/open?git_repo=https://github.com/googleapis/google-cloud-node&page=editor&open_in_editor=handwritten/logging/samples/generated/v2/metrics_service_v2.delete_log_metric.js,handwritten/logging/samples/README.md) |
| Metrics_service_v2.get_log_metric | [source code](https://github.com/googleapis/google-cloud-node/blob/main/handwritten/logging/samples/generated/v2/metrics_service_v2.get_log_metric.js) | [![Open in Cloud Shell][shell_img]](https://console.cloud.google.com/cloudshell/open?git_repo=https://github.com/googleapis/google-cloud-node&page=editor&open_in_editor=handwritten/logging/samples/generated/v2/metrics_service_v2.get_log_metric.js,handwritten/logging/samples/README.md) |
| Metrics_service_v2.list_log_metrics | [source code](https://github.com/googleapis/google-cloud-node/blob/main/handwritten/logging/samples/generated/v2/metrics_service_v2.list_log_metrics.js) | [![Open in Cloud Shell][shell_img]](https://console.cloud.google.com/cloudshell/open?git_repo=https://github.com/googleapis/google-cloud-node&page=editor&open_in_editor=handwritten/logging/samples/generated/v2/metrics_service_v2.list_log_metrics.js,handwritten/logging/samples/README.md) |
| Metrics_service_v2.update_log_metric | [source code](https://github.com/googleapis/google-cloud-node/blob/main/handwritten/logging/samples/generated/v2/metrics_service_v2.update_log_metric.js) | [![Open in Cloud Shell][shell_img]](https://console.cloud.google.com/cloudshell/open?git_repo=https://github.com/googleapis/google-cloud-node&page=editor&open_in_editor=handwritten/logging/samples/generated/v2/metrics_service_v2.update_log_metric.js,handwritten/logging/samples/README.md) |



The [Cloud Logging Node.js Client API Reference][client-docs] documentation
also contains samples.

## Supported Node.js Versions

Our client libraries follow the [Node.js release schedule](https://github.com/nodejs/release#release-schedule).
Libraries are compatible with all current _active_ and _maintenance_ versions of
Node.js.
If you are using an end-of-life version of Node.js, we recommend that you update
as soon as possible to an actively supported LTS version.

Google's client libraries support legacy versions of Node.js runtimes on a
best-efforts basis with the following warnings:

* Legacy versions are not tested in continuous integration.
* Some security patches and features cannot be backported.
* Dependencies cannot be kept up-to-date.

Client libraries targeting some end-of-life versions of Node.js are available, and
can be installed through npm [dist-tags](https://docs.npmjs.com/cli/dist-tag).
The dist-tags follow the naming convention `legacy-(version)`.
For example, `npm install @google-cloud/logging@legacy-8` installs client libraries
for versions compatible with Node.js 8.

## Versioning

This library follows [Semantic Versioning](http://semver.org/).



This library is considered to be **stable**. The code surface will not change in backwards-incompatible ways
unless absolutely necessary (e.g. because of critical security issues) or with
an extensive deprecation period. Issues and requests against **stable** libraries
are addressed with the highest priority.






More Information: [Google Cloud Platform Launch Stages][launch_stages]

[launch_stages]: https://cloud.google.com/terms/launch-stages

## Contributing

Contributions welcome! See the [Contributing Guide](https://github.com/googleapis/google-cloud-node/blob/main/CONTRIBUTING.md).

Please note that this `README.md`, the `samples/README.md`,
and a variety of configuration files in this repository (including `.nycrc` and `tsconfig.json`)
are generated from a central template. To edit one of these files, make an edit
to its templates in
[directory](https://github.com/googleapis/synthtool).

## License

Apache Version 2.0

See [LICENSE](https://github.com/googleapis/google-cloud-node/blob/main/LICENSE)

[client-docs]: https://cloud.google.com/nodejs/docs/reference/logging/latest
[product-docs]: https://cloud.google.com/logging/docs
[shell_img]: https://gstatic.com/cloudssh/images/open-btn.png
[projects]: https://console.cloud.google.com/project
[billing]: https://support.google.com/cloud/answer/6293499#enable-billing
[enable_api]: https://console.cloud.google.com/flows/enableapi?apiid=logging.googleapis.com
[auth]: https://cloud.google.com/docs/authentication/external/set-up-adc-local
