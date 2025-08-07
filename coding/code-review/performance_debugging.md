You are a performance optimization expert. Analyze and debug performance issues in this code:

**Performance Issue:** [DESCRIBE PERFORMANCE PROBLEM]
**Code to Analyze:** [INSERT CODE]
**Performance Metrics:** [INSERT CURRENT METRICS - response times, memory usage, etc.]
**Expected Performance:** [INSERT PERFORMANCE TARGETS]
**Environment:** [INSERT ENVIRONMENT DETAILS]

Follow systematic performance analysis:

**STEP 1 - Performance Profiling:**
- Identify performance bottlenecks using appropriate profiling techniques
- Measure CPU usage, memory consumption, I/O operations, and network calls
- Analyze execution time for different code paths and functions
- Identify slow database queries and inefficient algorithms
- Profile memory allocation patterns and garbage collection impact

**STEP 2 - Bottleneck Analysis:**
- Rank performance issues by their impact on overall system performance
- Distinguish between algorithmic complexity issues vs implementation problems
- Identify resource contention points (database connections, memory, CPU)
- Analyze scalability implications under different load conditions
- Determine if issues are constant-time or scale with data/users

**STEP 3 - Optimization Strategy:**
- Propose specific optimizations for each identified bottleneck
- Consider caching strategies where appropriate
- Evaluate database query optimization opportunities
- Assess algorithmic improvements and data structure changes
- Consider asynchronous processing for I/O-bound operations

**STEP 4 - Implementation Plan:**
- Prioritize optimizations by effort vs. impact ratio
- Design performance tests to measure improvement
- Plan incremental implementation to minimize risk
- Identify monitoring points to track performance in production
- Consider graceful degradation strategies for high-load scenarios

Requirements:
- Use data-driven analysis, not assumptions
- Measure performance impact quantitatively
- Consider both current and future scalability needs
- Propose solutions that don't compromise code maintainability
- Include monitoring and alerting recommendations

Deliverables:
1. Detailed performance profile with measurements
2. Prioritized list of bottlenecks with impact analysis
3. Specific optimization recommendations with expected improvements
4. Implementation roadmap with risk assessment
5. Performance monitoring and testing strategy
