# 100DaysOfSystemDesign
<a href="https://ibb.co/jTshZjr"><img src="https://i.ibb.co/473Wg0V/100-Days-Of-System-Design.png" alt="100-Days-Of-System-Design" border="0"></a>

System Design is all about building reliable, scalable and maintainable systems.

## Major Resources 📚

- Books
    - [ Designing data intensive applications](https://learning.oreilly.com/library/view/designing-data-intensive-applications/9781491903063/)
- Youtube Playlists
    - [System Design By Gaurav Sen](https://www.youtube.com/playlist?list=PLMCXHnjXnTnvo6alSjVkgxV-VH6EPyvoX)
- Github Repos
    - [System Design primer](https://github.com/donnemartin/system-design-primer)
- Courses
    - [Web Application and Software Architecture 101](https://www.educative.io/courses/web-application-software-architecture-101) (accessible using Github student dev pack)

##  Progress ⏳
### Day 1
- [Web Architecture basics](https://www.youtube.com/watch?v=AYHE2m651dY) 
- [Different Tiers in Software Architecture](https://www.educative.io/courses/web-application-software-architecture-101) (module 2)

### Day 2
- [Web Architecture](https://www.educative.io/courses/web-application-software-architecture-101) - (module 3)
    - client-server
    - types of clients
    - REST API
- [HTTP PUSH, PULL](https://nlogn.in/http-push-and-pull-introduction/)

### Day 3
- [HTTP PULL - Polling with ajax](https://www.educative.io/courses/web-application-software-architecture-101) - (module 3)
- [Persistent Connection Approaches(HTTP PUSH)](https://youtu.be/k56H0DHqu5Y)
    - HTTP Polling
    - HTTP Long polling
    - web socket
    - server send events
    - Streaming over HTTP

### Day 4
- Scalability 
    - [what is scalability](https://youtu.be/OjOUNhBE404)
    - [horizontal vs vertical](https://youtu.be/r7X5U7jXXRw)
    - [scaling for global audience](https://youtu.be/29gJ6BUpw0M)
        - vertical and horizontal scaling
        - isolation of services
        - CDN
        - Edge cache
        - Geo-DNS

### Day 5
- [Scalability- module 4](https://www.educative.io/courses/web-application-software-architecture-101)
    - application latency vs n/w latency
    - Primary bottlenecks for scalability - databases, application architecture, caching, load balancers etc
- [Performance vs scalability](https://github.com/donnemartin/system-design-primer#performance-vs-scalability)

### Day 6
- Throughput vs Latency
    - [Understanding Latency vs Througput](https://community.cadence.com/cadence_blogs_8/b/sd/posts/understanding-latency-vs-throughput?Redirected=true)
    - Measuring Latency: average, p90, p99 etc
        - [Percentile Tail Latency](https://www.youtube.com/watch?v=3JdQOExKtUY)

### Day 7
- Availability vs Consistency
    - [Understanding C,A,P](https://youtu.be/pSoKUfLTe8Y)
    - [CAP Theorem](https://youtu.be/kwCFHLbIhak)

### Day 8
- [Eventual consistency vs strong consistency](https://hackernoon.com/eventual-vs-strong-consistency-in-distributed-databases-282fdad37cf7)
- [ACID vs BASE in Databases](https://medium.com/geekculture/acid-vs-base-in-databases-1bcad774da26)
- Further read on CAP theorem -
    - https://www.infoq.com/articles/cap-twelve-years-later-how-the-rules-have-changed/

### Day 9
- [High Availability- module 5](https://www.educative.io/courses/web-application-software-architecture-101)
    - fault tolerance, redundancy, replication, HA clustering

### Day 10
- [Hashing](https://www.youtube.com/watch?v=cITtFpz3a3Y)
- [Consistent Hashing](https://www.youtube.com/watch?v=oKAU6LaYFhw)
- [Consistent Hashing](https://www.youtube.com/watch?v=zaRkONvyGr8)

### Day 11
- [Load Balancing](https://afteracademy.com/blog/what-is-load-balancing-how-does-it-work)
- [Load balancing using consistent hashing](https://nlogn.in/consistent-hashing-system-design/)

### Day 12 
- [Monolith vs Microservices - module 6](https://www.educative.io/courses/web-application-software-architecture-101)

### Day 13
- [Reverse proxy web server](https://github.com/donnemartin/system-design-primer#reverse-proxy-web-server)
- [Proxy vs Reverse Proxy](https://www.youtube.com/watch?v=SqqrOspasag)

### Day 14

- [Databases - module 7](https://www.educative.io/courses/web-application-software-architecture-101)
    - relational vs non relational, polyglot persistence, types of dbs 
 
 ### Day 15
 - [Database scaling using Replication](https://youtu.be/RIcNswROzCc)
    - master-slave, master-master architecture
    - replication lag
    - synchronous vs async replication
    - replica vs snapshot

### Day 16
- [Database Sharding](https://medium.com/@jeeyoungk/how-sharding-works-b4dec46b3f6)
    - vertical vs horizontal sharding
    - logical vs physical shards
    - sharding strategies - dynamic, algorithmic
    - advantages and pitfalls
