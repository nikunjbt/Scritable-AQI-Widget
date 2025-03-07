# Scritable-AQI-Widget
Check AQI Based on your location directly on the widget

Icons Added:<br>
📍 for location (top section)<br>
💨 for AQI value (middle section)<br>

Level-specific icons in getAQILevel:<br>
🌳 (Very Good)<br>
🌞 (Good)<br>
🌥️ (Moderate)<br>
🌫️ (Unhealthy)<br>
💨 (Very Unhealthy)<br>
☠️ (Hazardous)<br>
⚠️ for error state<br>

Visual Enhancements:<br>
  Increased spacing with widget.addSpacer(8) for better layout <br>
  Added semi-transparent background to level text using the level's color<br>
  Adjusted font sizes and spacing for better readability<br>
  Used horizontal stacks consistently for icon-text pairing<br>

Error Display:<br>
  Added warning icon to error message<br>
  Centered error content using a stack<br>

Limitations and Notes:<br>

  Scriptable doesn't natively support importing custom images, so I've used emojis as icons<br>
  The widget uses a medium size layout for best presentation<br>
  Colors and transparency are maintained from your original gradient design<br>
  Replace "YOUR_API_KEY_HERE" with your actual IQAir API key<br>

This version should give you a more visually appealing widget with iconography while maintaining the core functionality. <br>
The icons provide quick visual cues about the air quality status and location context. Run it in Scriptable.
