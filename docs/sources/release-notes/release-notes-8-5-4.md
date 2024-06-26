+++
aliases = ["/docs/grafana/latest/release-notes/release-notes-8-5-4/"]
hide_menu = true
title = "Release notes for Grafana 8.5.4"
+++

<!-- Auto generated by update changelog github action -->

# Release notes for Grafana 8.5.4

### Features and enhancements

- **Alerting:** Remove disabled flag for data source when migrating alerts. [#48559](https://github.com/grafana/grafana/pull/48559), [@yuri-tceretian](https://github.com/yuri-tceretian)
- **Alerting:** Show notification tab of legacy alerting only to editor. [#49624](https://github.com/grafana/grafana/pull/49624), [@yuri-tceretian](https://github.com/yuri-tceretian)
- **Alerting:** Update migration to migrate only alerts that belong to existing org\dashboard. [#49192](https://github.com/grafana/grafana/pull/49192), [@yuri-tceretian](https://github.com/yuri-tceretian)
- **AzureMonitor:** Do not quote variables when a custom "All" variable option is used. [#49428](https://github.com/grafana/grafana/pull/49428), [@andresmgot](https://github.com/andresmgot)
- **AzureMonitor:** Update allowed namespaces. [#48468](https://github.com/grafana/grafana/pull/48468), [@jcolladokuri](https://github.com/jcolladokuri)
- **CloudMonitor:** Correctly encode default project response. [#49510](https://github.com/grafana/grafana/pull/49510), [@aangelisc](https://github.com/aangelisc)
- **Cloudwatch:** Add support for new AWS/RDS EBS\* metrics. [#48798](https://github.com/grafana/grafana/pull/48798), [@szymonpk](https://github.com/szymonpk)
- **InfluxDB:** Use backend for influxDB by default via feature toggle. [#48453](https://github.com/grafana/grafana/pull/48453), [@yesoreyeram](https://github.com/yesoreyeram)
- **Legend:** Use correct unit for percent and count calculations. [#49004](https://github.com/grafana/grafana/pull/49004), [@dprokop](https://github.com/dprokop)
- **LokI:** use millisecond steps in Grafana 8.5.x. [#48630](https://github.com/grafana/grafana/pull/48630), [@gabor](https://github.com/gabor)
- **Plugins:** Introduce HTTP 207 Multi Status response to api/ds/query. [#48550](https://github.com/grafana/grafana/pull/48550), [@wbrowne](https://github.com/wbrowne)
- **Reporting:** Improve PDF file size using grid layout. (Enterprise)
- **Transformations:** Add an All Unique Values Reducer. [#48653](https://github.com/grafana/grafana/pull/48653), [@josiahg](https://github.com/josiahg)
- **Transformers:** avoid error when the ExtractFields source field is missing. [#49368](https://github.com/grafana/grafana/pull/49368), [@wardbekker](https://github.com/wardbekker)
- **[v8.5.x] Alerting:** Update migration to migrate only alerts that belong to existing org\dashboard. [#49199](https://github.com/grafana/grafana/pull/49199), [@grafanabot](https://github.com/grafanabot)
- **[v8.5.x] Reporting:** Improve PDF file size using grid layout. (Enterprise)

### Bug fixes

- **Alerting:** Allow disabling override timings for notification policies. [#48648](https://github.com/grafana/grafana/pull/48648), [@gillesdemey](https://github.com/gillesdemey)
- **Alerting:** Allow serving images from custom url path. [#49022](https://github.com/grafana/grafana/pull/49022), [@gillesdemey](https://github.com/gillesdemey)
- **Alerting:** Apply Custom Headers to datasource queries. [#47860](https://github.com/grafana/grafana/pull/47860), [@joeblubaugh](https://github.com/joeblubaugh)
- **Alerting:** Fix RBAC actions for notification policies. [#49185](https://github.com/grafana/grafana/pull/49185), [@yuri-tceretian](https://github.com/yuri-tceretian)
- **Alerting:** Fix access to alerts for viewer with editor permissions when RBAC is disabled. [#49270](https://github.com/grafana/grafana/pull/49270), [@yuri-tceretian](https://github.com/yuri-tceretian)
- **Alerting:** Fix anonymous access to alerting. [#49203](https://github.com/grafana/grafana/pull/49203), [@yuri-tceretian](https://github.com/yuri-tceretian)
- **Alerting:** correctly show all alerts in a folder. [#48684](https://github.com/grafana/grafana/pull/48684), [@gillesdemey](https://github.com/gillesdemey)
- **AzureMonitor:** Fixes metric definition for Azure Storage queue/file/blob/table resources. [#49101](https://github.com/grafana/grafana/pull/49101), [@aangelisc](https://github.com/aangelisc)
- **Dashboard:** Fix dashboard update permission check. [#48746](https://github.com/grafana/grafana/pull/48746), [@IevaVasiljeva](https://github.com/IevaVasiljeva)
- **DashboardExport:** Fix exporting and importing dashboards where query data source ended up as incorrect. [#48410](https://github.com/grafana/grafana/pull/48410), [@torkelo](https://github.com/torkelo)
- **FileUpload:** clicking the `Upload file` button now opens the modal correctly. [#48766](https://github.com/grafana/grafana/pull/48766), [@ashharrison90](https://github.com/ashharrison90)
- **GrafanaUI:** Fix color of links in error Tooltips in light theme. [#49327](https://github.com/grafana/grafana/pull/49327), [@joshhunt](https://github.com/joshhunt)
- **LibraryPanels:** Fix library panels not connecting properly in imported dashboards. [#49161](https://github.com/grafana/grafana/pull/49161), [@joshhunt](https://github.com/joshhunt)
- **Loki:** Improve unpack parser handling. [#49074](https://github.com/grafana/grafana/pull/49074), [@gabor](https://github.com/gabor)
- **RolePicker:** Fix menu position on smaller screens. [#48429](https://github.com/grafana/grafana/pull/48429), [@Clarity-89](https://github.com/Clarity-89)
- **TimeRange:** Fixes updating time range from url and browser history. [#48657](https://github.com/grafana/grafana/pull/48657), [@torkelo](https://github.com/torkelo)
- **TimeSeries:** Fix detection & rendering of sparse datapoints. [#48841](https://github.com/grafana/grafana/pull/48841), [@leeoniya](https://github.com/leeoniya)
- **Timeseries:** Fix outside range stale state. [#49633](https://github.com/grafana/grafana/pull/49633), [@ryantxu](https://github.com/ryantxu)
- **Tooltip:** Fix links not legible in Tooltips when using light theme. [#48748](https://github.com/grafana/grafana/pull/48748), [@joshhunt](https://github.com/joshhunt)
- **Tooltip:** Sort decimals using standard numeric compare. [#49084](https://github.com/grafana/grafana/pull/49084), [@dprokop](https://github.com/dprokop)
- **Transforms:** Labels to fields, fix label picker layout. [#49304](https://github.com/grafana/grafana/pull/49304), [@torkelo](https://github.com/torkelo)
- **Variables:** Fixes issue with data source variables not updating queries with variable. [#49478](https://github.com/grafana/grafana/pull/49478), [@torkelo](https://github.com/torkelo)
- **[v8.5.x] Alerting:** Fix RBAC actions for notification policies (#49185). [#49348](https://github.com/grafana/grafana/pull/49348), [@yuri-tceretian](https://github.com/yuri-tceretian)
- **[v8.5.x] Alerting:** Fix access to alerts for viewer with editor permissions when RBAC is disabled. [#49427](https://github.com/grafana/grafana/pull/49427), [@konrad147](https://github.com/konrad147)
- **[v8.5.x] Alerting:** Fix anonymous access to alerting. [#49268](https://github.com/grafana/grafana/pull/49268), [@yuri-tceretian](https://github.com/yuri-tceretian)

### Breaking changes

For a data source query made via /api/ds/query :

- If the `DatasourceQueryMultiStatus` feature is enabled and
  - The data source response has an error set as part of the `DataResponse`, the resulting HTTP status code is now `207 Multi Status` instead of `400 Bad gateway`
- If the `DatasourceQueryMultiStatus` feature is **not** enabled and
  - The data source response has an error set as part of the `DataResponse`, the resulting HTTP status code is `400 Bad Request` (no breaking change)
    --> Issue [#48550](https://github.com/grafana/grafana/issues/48550)
