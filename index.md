---
title:
layout: default
---

Dyna&#969;o
Dyna&omega;

```modelica
model Test
  parameter Real a = 1;
  parameter Real b = 2;
  Real u (start = 1);
equation
  a*der(u) = -b*u;
end Test;
```

~~~modelica
model Test
  parameter Real a = 1;
  parameter Real b = 2;
  Real u (start = 1);
equation
  a*der(u) = -b*u;
end Test;
~~~

```cpp
public Class {
  public:
    int data_;
}
```
