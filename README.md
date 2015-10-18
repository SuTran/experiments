# My Experiments
This repository aims to improve my skills on programing

### Web performance

1. Web worker
2. requestAnimationFrame
3. Forced Synchronous Layout
  * pizz-perf-master

4. Timing API

```javascript
window.performance.mark('mark_fully_loaded');
```

```javascript
window.performance.measure('measure_load_from_dom', 'domComplete', 'mark_fully_loaded');
```

5. Reduce 'Recalculate styles' total time
  * Reduce number of affected elements
  * Reduce the slectors complexity
