# synthetic monitoring
Synthetic monitoring is used to check the availability of a service, automated end-to-end testing is performanced on a regular interval (more frequency on critical paths) 24/7 from the end-user perspective. This form of monitoring is effectively good for services with multiple failure points, especially for service which a heavily reliant on 3rd party services.

# health checks
Individual point of failures should be health checked, the intent is to quickly identify the point of failure as quickly as possible. Any breaks in the integration circuit will be detected and attention will be drawn to that point of failure so it can be quickly diagnosed.

https://martinfowler.com/bliki/SyntheticMonitoring.html

https://dzone.com/articles/synthetic-monitoring-why-amp-when-to-use-it

https://www.uptrends.com/what-is/synthetic-monitoring

https://aws.amazon.com/builders-library/implementing-health-checks/
