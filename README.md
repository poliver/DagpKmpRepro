# DagpKmpRepro

DAGP advice is:
```
Advice for :app
These transitive dependencies should be declared directly:
  implementation("androidx.compose.foundation:foundation-layout:1.6.0-alpha06") { capabilities {
    requireCapability("androidx.compose.foundation:foundation-layout")
  }}
  implementation("androidx.compose.foundation:foundation:1.6.0-alpha06") { capabilities {
    requireCapability("androidx.compose.foundation:foundation")
  }}
  implementation("androidx.compose.material3:material3:1.2.0-alpha08") { capabilities {
    requireCapability("androidx.compose.material3:material3")
  }}
  implementation("androidx.compose.runtime:runtime:1.6.0-alpha06") { capabilities {
    requireCapability("androidx.compose.runtime:runtime")
  }}
  implementation("androidx.compose.ui:ui-graphics:1.6.0-alpha06") { capabilities {
    requireCapability("androidx.compose.ui:ui-graphics")
  }}
  implementation("androidx.compose.ui:ui-text:1.6.0-alpha06") { capabilities {
    requireCapability("androidx.compose.ui:ui-text")
  }}
  implementation("androidx.compose.ui:ui-tooling-preview:1.6.0-alpha06") { capabilities {
    requireCapability("androidx.compose.ui:ui-tooling-preview")
  }}
  implementation("androidx.compose.ui:ui-unit:1.6.0-alpha06") { capabilities {
    requireCapability("androidx.compose.ui:ui-unit")
  }}
  implementation("androidx.compose.ui:ui:1.6.0-alpha06") { capabilities {
    requireCapability("androidx.compose.ui:ui")
  }}

```
