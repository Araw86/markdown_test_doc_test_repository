# Add ThreadX to CubeMX project

v2.0.0

No language

```
#define TRACEX_BUFFER_SIZE 64000
uint8_t tracex_buffer[64000];
```

c

```c
#define TRACEX_BUFFER_SIZE 64000
uint8_t tracex_buffer[64000];
```

c-nc

```c-nc
#define TRACEX_BUFFER_SIZE 64000
uint8_t tracex_buffer[64000];
```

json

```json
{ "filesToLoadArr": [
    {
      "name": "1. Add ThreadX",
      "path": "/theory_utility",
      "file": "add_threadx.md"
    },
    {
      "name": "2. Add TraceX",
      "path": "/theory_utility",
      "file": "adding_tracex.md"
    }
}
```

```json-line1
{ "filesToLoadArr": [
    {
      "name": "1. Add ThreadX",
      "path": "/theory_utility",
      "file": "add_threadx.md"
    },
    {
      "name": "2. Add TraceX",
      "path": "/theory_utility",
      "file": "adding_tracex.md"
    }
}
```

```json-line1-filemain.c-nc
{ "filesToLoadArr": [
    {
      "name": "1. Add ThreadX",
      "path": "/theory_utility",
      "file": "add_threadx.md"
    },
    {
      "name": "2. Add TraceX",
      "path": "/theory_utility",
      "file": "adding_tracex.md"
    }
}
```

```json-line1-nc-filemain.c
{ "filesToLoadArr": [
    {
      "name": "1. Add ThreadX",
      "path": "/theory_utility",
      "file": "add_threadx.md"
    },
    {
      "name": "2. Add TraceX",
      "path": "/theory_utility",
      "file": "adding_tracex.md"
    }
}
```

json-nc

```json-nc
{ "filesToLoadArr": [
    {
      "name": "1. Add ThreadX",
      "path": "/theory_utility",
      "file": "add_threadx.md"
    },
    {
      "name": "2. Add TraceX",
      "path": "/theory_utility",
      "file": "adding_tracex.md"
    }
}
```

```json-nc
{ "filesToLoadArr": [
    {
      "name": "1. Add ThreadX",
      "path": "/theory_utility",
      "file": "add_threadx.md"
    },
    {
      "name": "2. Add TraceX",
      "path": "/theory_utility",
      "file": "adding_tracex.md"
    }
}
```

## Software Pack

In CubeMX Tab:

1. Software packs
2. Select components

![Software pack open](./img/06.png)

1. Open X-Cube-Azure-H7
2. Opne RTOS
   1. Select ThreadX / Core
   2. Select ThreadX / PerformanceInfo
   3. Select ThreadX / TraceX support
3. Open Device
   1. Select HW_Profile: STM32H723ZG_NUCLEO
   2. Select Application: azure_rtos_app
4. Click OK

![ThreadX pack selection](./img/07.png)

## Configure ThreadX mode

1. Select software packs
2. Select X-Cube-Azure-H7
3. In mode
   1. Check Device AZURE RTOS Applications
   2. RTOS ThreadX
4. Save project CTRL+S(this will generate ThreadX files to our project)

![ThreadX pack mode](./img/08.png)
