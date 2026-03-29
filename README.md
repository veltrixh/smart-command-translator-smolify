# smart-command-translator-smolify

Modern smart systems (IoT devices, APIs, automation platforms) require structured commands (JSON) to function.

However, users naturally communicate in unstructured natural language, which creates a gap between human intent and machine execution.

Examples:

“Turn off the kitchen lights at 10 pm”
“Set the thermostat to 72 degrees”

These cannot be directly used by machines without transformation.

SOLUTION:

We built a Smart Command Translator that converts natural language into structured JSON commands in real time.

Example:

Input:

Turn off the kitchen lights at 10 pm

Output:

{
  "device": "lights",
  "action": "off",
  "location": "kitchen",
  "time": "22:00"
}

The system enables seamless interaction between users and automation systems.
