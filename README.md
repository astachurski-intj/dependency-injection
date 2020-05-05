# dependency-injection
All DI types, @RestController, @SpringBootTest, @MockBean, mocking REST endpoint for tests, @LocalServerPoint

This is intense exercise - multiple concepts coming together in one simple application serving "cars" via REST.

3 types of dependency injection in one place

Mocking REST endpoint. Using MockMVC.

The most important takeaway is delegation via dependency injection, hiding implementation details behind interfaces and
the fact that SpringBoot handles marshalling (conversions) of data types automatically most of the time. This is explained
using simple DTO (data transfer object).
