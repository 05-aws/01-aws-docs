## Scalability

- The ability to `automatically adjust resources` (like compute power or storage) based on demand
- It can be
  . `Horizontal Scaling (= Elasticity)`
  => Adding/removing instances
  => No limit usually

  . `Vertical Scaling`
  => `Increase size` of a single instance (CPU, RAM, Storage...). Ex: `t2.micro => t2.large`
  => Prevent by hardware limits

## High Availability

- Means ensuring your application or service `stays up and running`, even if `some components fail`
- This is achieved by `distributing resources` across `multiple Availability Zones (AZs)` in a region
