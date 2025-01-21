# Khái niệm nâng cao

## Anchor và Alias
Ví dụ:

```yaml
definitions:
  weekday: &working
    wakeup: 6:00 AM
    activities:
      - workout
      - work
      - sleep
    sleeptime: 10:00 PM
  weekend: &holiday
    wakeup: 8:00 AM
    activities:
      - workout
      - movies
      - sleep
    sleeptime: 11:00 PM
schedules:
  weekdays:
    - monday: *working
    - tuesday: *working
    - wednesday: *working
    - thirdday: *working
    - friday: *working
  weekends:
    - saturday: *holiday
    - sunday: *holiday
```
## Multi-line string
Ví dụ:

```yaml
literal_style: |
  Lorem ipsum dolor sit amet sed diam illum clita lorem et diam mazim.
  Ut eirmod dolor.
  Et magna ipsum nam est sit et elitr lorem labore justo.
  Et invidunt luptatum vel dolore nam lorem stet kasd nibh lorem nulla dolor consequat eum rebum sed.

folded_block: >
  Lorem ipsum dolor sit amet sed diam illum clita lorem et diam mazim.
  Ut eirmod dolor. Et magna ipsum nam est sit et elitr lorem labore justo.
  Et invidunt luptatum vel dolore nam lorem stet kasd nibh lorem nulla dolor consequat eum rebum sed.
```
