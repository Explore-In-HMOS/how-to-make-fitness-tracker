> **Note:** To access all shared projects, get information about environment setup, and view other guides, please visit [Explore-In-HMOS Index](https://github.com/Explore-In-HMOS/hmos-index).

# How To Make Fitness Tracker

This HarmonyOS application helps users perform interval training with configurable work/rest periods.  
It tracks rounds visually, shows color-coded phase indicators, and provides start/pause/reset controls.  
The goal is to demonstrate a simple yet responsive fitness timer with a clean modular UI and separate business logic.

# Preview

<div>
  <img src="./screenshots/Animated.gif" width="24%">
</div>

# Use Cases

- Track configurable work/rest intervals during workouts
- Monitor training progress through visual round indicators
- Start, pause, and reset workout sessions easily
- Use on HarmonyOS devices or simulator

# Tech Stack

- **Languages**: ArkTS, ArkUI
- **Frameworks**: HarmonyOS SDK 5.0.2(14)
- **Tools**: DevEco Studio Version 5.1.0.828
- **Libraries**:
    - `@kit.AbilityKit`
    - `@kit.ArkUI`
    - `@kit.PerformanceAnalysisKit`

# Directory Structure

```
├── entry/
│ └── src/
│ ├── main/
│ │ ├── ets/
│ │ │ ├── entryability/ 
│ │ │ │ └── EntryAbility.ets 
│ │ │ ├── entrybackupability/ 
│ │ │ │ └── EntryBackupAbility.ets 
│ │ │ ├── models/ 
│ │ │ │ └── WorkoutTimerModel.ets # logic implementation
│ │ │ ├── pages/ 
│ │ │ │ └── Index.ets # Fitness timer implementation

```

# Constraints and Restrictions

## Supported Devices

- Huawei Watch 5

# LICENSE

**Fitness Tracker** is distributed under the terms of the MIT License.  
See the [LICENSE](LICENSE) for more information.