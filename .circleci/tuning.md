
## Origin

Gradle command from jenkins build - clean and test are core commands repeated in parallel across multiple JDK versions rangin from 8 to 17.
https://ci-builds.apache.org/job/Kafka/job/kafka-pr/job/PR-12771/2/flowGraphTable/

## Modifications

- Caching the gradle dependencies
- sxlarge+ (20/40) docker executor