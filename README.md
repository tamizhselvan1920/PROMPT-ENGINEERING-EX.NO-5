# EXP 5: COMPARATIVE ANALYSIS OF DIFFERENT TYPES OF PROMPTING PATTERNS AND EXPLAIN WITH VARIOUS TEST SCENARIOS

# Aim:
To test and compare how different pattern models respond to various prompts (broad or unstructured) versus basic prompts (clearer and more refined) across multiple scenarios.  Analyze the quality, accuracy, and depth of the generated responses 

### AI Tools Required: CHATGPT

# Explanation: 
Define the Two Prompt Types:

Write a basic Prompt: Clear, detailed, and structured prompts that give specific instructions or context to guide the model.
Based on that pattern type refined the prompt and submit that with AI tool.
Get the ouput and write the report.

Prepare Multiple Test Scenarios:
Select various scenarios such as:
Generating a creative story.
Answering a factual question.
Summarizing an article or concept.
Providing advice or recommendations.
Or Any other test scenario
For each scenario, create both a naïve and a basic prompt. Ensure each pair of prompts targets the same task but with different levels of structure.
Run Experiments with ChatGPT:
Input the naïve prompt for each scenario and record the generated response.
Then input the corresponding basic prompt and capture that response.
Repeat this process for all selected scenarios to gather a full set of results.
Evaluate Responses : 
	Compare how ChatGPT performs when given naïve versus basic prompts and analyze the output based on Quality,Accuracy and Depth. Also analyse does ChatGPT consistently provide better results with basic prompts? Are there scenarios where naïve prompts work equally well?
Deliverables:
A table comparing ChatGPT's responses to naïve and basic prompts across all scenarios.
Analysis of how prompt clarity impacts the quality, accuracy, and depth of ChatGPT’s outputs.
Summary of findings with insights on how to structure prompts for optimal results when using ChatGPT.


# OUTPUT

# 1. Basic Prompt

A **basic prompt** is simple and direct but may not guide the model strongly.

**Prompt:**
“Explain the working principle of a temperature sensor used in industrial applications.”

### Expected Response Characteristics

* General explanation
* May not include examples or structured reasoning
* Moderate detail

### Sample Response (Condensed)

Temperature sensors are devices used to measure temperature in industrial processes. Common sensors include thermocouples and RTDs. A thermocouple works based on the Seebeck effect where two different metals generate voltage when exposed to temperature differences. RTDs measure temperature by changes in electrical resistance of a metal element. These sensors send signals to control systems to monitor and regulate temperature.


# 2. Zero-Shot Prompt

A **zero-shot prompt** asks the model to perform a task **without examples**, but with clearer instructions.

**Prompt:**
“Explain the working principle of an industrial temperature sensor in about 150–200 words. Include the principle, components, and one example such as a thermocouple or RTD.”

### Expected Response Characteristics

* More structured
* Includes specific information requested

### Sample Response

Industrial temperature sensors measure temperature and convert it into an electrical signal that can be monitored or controlled. One common sensor is the thermocouple. A thermocouple consists of two different metal wires joined at one end called the junction. When this junction experiences a temperature change, a voltage is generated due to the Seebeck effect. This voltage is proportional to the temperature difference between the measuring junction and the reference junction.

Another widely used sensor is the Resistance Temperature Detector (RTD). RTDs operate on the principle that the electrical resistance of metals increases with temperature. The sensor element is typically made of platinum. When temperature rises, the resistance of the platinum element increases, and this change is measured and converted into temperature readings.

These sensors are widely used in power plants, manufacturing industries, and chemical processes for accurate temperature monitoring and control.


# 3. Few-Shot Prompt

A **few-shot prompt** includes examples to guide the model.

**Prompt:**

Explain the working principle of an industrial sensor. Follow the format shown in the examples.

Example 1
Sensor: Pressure Sensor
Working Principle: Pressure sensors convert applied pressure into electrical signals using strain gauges. When pressure is applied, the sensor element deforms, changing electrical resistance.

Example 2
Sensor: Light Sensor
Working Principle: Light sensors detect light intensity using photoelectric effects. When light strikes the sensor material, it generates a current proportional to light intensity.

Now explain:

Sensor: Temperature Sensor

### Expected Response Characteristics

* Follows the same format
* More consistent output

### Sample Response

Sensor: Temperature Sensor

Working Principle: Temperature sensors measure heat and convert it into electrical signals. One common type is the thermocouple, which works on the Seebeck effect. When two dissimilar metals are joined and exposed to temperature differences, a small voltage is produced. This voltage corresponds to the temperature difference and is measured by electronic circuits. Another type is the RTD, which operates on the principle that the resistance of a metal increases with temperature. The resistance change is measured and converted into temperature readings used for industrial monitoring and control.


# 4. Chain-of-Thought Prompt

A **chain-of-thought prompt** encourages the model to explain reasoning step-by-step.

**Prompt:**
“Explain the working principle of a temperature sensor used in industry. Think step-by-step and describe the process from sensing temperature to producing an electrical output signal.”

### Expected Response Characteristics

* Step-by-step explanation
* Deeper reasoning

### Sample Response

Step 1: Identify the physical quantity to measure
The sensor first detects temperature, which represents the heat energy of a system.

Step 2: Use a sensing element
In a thermocouple, two dissimilar metals are joined together to form a sensing junction.

Step 3: Apply a physical principle
When the junction experiences a temperature difference compared to a reference junction, the Seebeck effect occurs.

Step 4: Generate an electrical signal
Due to the Seebeck effect, a small voltage is produced across the metals.

Step 5: Convert signal to readable output
The voltage is measured by electronic circuits and converted into a temperature reading.

Step 6: Send the signal to control systems
The measured temperature is displayed or used in industrial automation systems for process control.


# Evaluation of Prompting Techniques

### Evaluation Method: **Qualitative Response Analysis**

Criteria used:

1. **Accuracy**
2. **Clarity**
3. **Depth of Explanation**
4. **Structure**

| Prompt Type      | Accuracy | Clarity   | Depth  | Structure       |
| ---------------- | -------- | --------- | ------ | --------------- |
| Basic Prompt     | Medium   | Medium    | Low    | Unstructured    |
| Zero-shot Prompt | High     | High      | Medium | Organized       |
| Few-shot Prompt  | High     | High      | Medium | Very consistent |
| Chain-of-Thought | High     | Very High | High   | Step-by-step    |


# Analysis

### 1. Basic Prompt

* Provides general information.
* Lack of structure may reduce clarity.

### 2. Zero-Shot Prompt

* More precise instructions improve response quality.
* Balanced explanation.

### 3. Few-Shot Prompt

* Examples guide the model strongly.
* Output follows a predictable structure.

### 4. Chain-of-Thought Prompt

* Provides deeper reasoning.
* Best for **technical and problem-solving tasks**, especially useful for engineering concepts.


# Conclusion

Different prompting techniques significantly affect the quality of responses.

* **Basic prompts** are simple but less controlled.
* **Zero-shot prompts** improve clarity and detail.
* **Few-shot prompts** ensure consistent formatting and better accuracy.
* **Chain-of-thought prompts** produce the most detailed and logically structured responses.


# RESULT:
The prompt for the above said problem executed successfully
