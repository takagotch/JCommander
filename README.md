### jcommander
---
http://jcommander.org/

```java
import com.beust.jcommander.Parameter;

public class Args {
  @Parameter
  private List<String> parameters = new ArrayList<>();
  
  @Parameter(names = { "-log", "-verbose" }, description = "Level of verbosity")
  private Integer verbose = 1;
  
  @Parameter(names = "-groups", description = "Comma-separated list of group names to be run")
  private String groups;
  
  @Parameter(names = "-debug", description = "Debug mode")
  private boolean debug = false;
}
```

```
```

```
```
