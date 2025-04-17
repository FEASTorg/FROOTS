# FROOT

FROOT is a modular firmware base/template designed for single-function embedded devices that:

- 🔧 **Perform a dedicated control task** (e.g., temperature regulation, motor control).
- 🧠 **Execute all logic locally**, maintaining autonomy and robustness.
- 🔄 **Accept optional supervisor commands** for configuration or coordination.
- 🛡️ **Continue safe, deterministic operation** even if the supervisor becomes unavailable.
- ⏱️ **Support scheduled or profiled behavior**, such as ramping temperature or timed sequences.
- 🤝 **Enable distributed deployment**, where each device operates independently or as part of a networked system.
- 🔌 **Respond appropriately to supervision loss**, using fallback behaviors or hold-states rather than failing unsafely.
