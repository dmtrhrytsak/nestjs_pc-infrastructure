## Mocking simple computer infrastructure in the nestJS world
The objective of this app is to practice DI(dependency injection) in nestJS

**Modules:**
- ComputerModule
- CpuModule
- DiskModule

**Services:**
- <code>CpuService</code> depends on <code>PowerService</code>
- <code>DiskService</code> depends on <code>PowerService</code>

**Controllers:**
- <code>ComputerController</code> - the main entry of the app; runs <code>cpuService.compute()</code> && <code>diskService.getData()</code> methods.
