# PyCon and PyData 2025 (Virtual attendance)

## Are LLMs the answer to all our problems? 
### _Presented by Dr. Maria Börner_

### Notes

* **AI Bias Concerns**: 
  * Image Generation with LLM continues to show significant bias issues

* **Regulatory Framework**:
  * **EU AI Act**: Designed to prevent bias and protect human rights
  * **Regulatory Conflicts**:
    * With GDPR:
      - Mass data collection requirements
      - Automated decision-making processes
      - Right to be forgotten complications
    * With Copyright law: Unresolved ownership questions

* **Environmental Impact**:
  * **Carbon Footprint Comparisons**:
    * Average German resident: 10t CO₂ per year
    * US car lifetime (production + fuel): 57t CO₂
    * OpenAI's GPT-3 training: 500t CO₂
    * 1,000 text generation requests: 5g CO₂
    * 1,000 image generation requests: 200g CO₂

---

## The aesthetics of AI: from cyberpunk to fascism
### _Presented by Laura Summers_

### _Key Takeaways:_

* **Aesthetic Foundations**:
  * Definition: The philosophy of beauty and goodness
  * Interdisciplinary nature: Connects Philosophy, Art, Politics, Culture, Architecture
  * Sociopolitical dimension: Aesthetic elements reflect ideology and culture (e.g., Nazi Germany)

* **Architectural Movements & AI Design**:
  * Key styles: Modernism, Post-Modernism, Brutalism
  * AI Interface comparison: Clippy vs Claude AI aesthetic differences

* **Case Study: Tesla Cybertruck**:
  * Design influences: 
    - Brutalism, Modernism, Futurism, and Cyberpunk
  * Critical perspective: Potential symbolism of fascist aesthetics

* **Historical Context: Fascist Italian Futurism**:
  * Central concept: Aesthetic power superseding ethical considerations

* **Corporate Aesthetic Comparison**:
  * Uber: Prioritizes real-world imagery (people, nature) with technology integration
  * OpenAI: Technological aesthetic dominance, even in representational imagery

* **Emerging Trend**: "New American Futurism"

* **Physical Manifestations**:
  * Datacenter design elements: Futurism, Brutalism, and Modernism

---

## LLM Inference Arithmetics: the Theory of Model Serving
### _Presented by Luca Baggi_
### _Key Takeaways:_

* **Training vs Inference Paradigms**:
  * Training: Parallel processing architecture
  * Inference: Serial processing architecture
  * Transformers follow the same pattern: parallel training, serial inference

* **Processing Optimizations**: 
  * Asynchronous batch processing
  * Prompt engineering techniques

* **Resource Calculation Framework**:
  * **Key Dimensions**: Training and Inference
  * **Critical Quantities**:
    - Parameters (model size)
    - Memory requirements
    - Compute resources

* **Memory Size Formulas**:
  * Parameters represented as "D", Batch size as "B"
  * Inference calculation: D1 × D2
  * Training calculation: (B × D1) + (B × D2)
  * Advanced transformer models require significantly more complex calculations

* **Optimization Strategies**:
  * Hardware utilization (GPU vs storage)
  * Computational efficiency through batching techniques
  * Processing mode selection (parallel vs serial)
  * Tool selection based on specific requirements

---

## Inclusive Data for 1.3 Billion: Designing Accessible Visualizations
### _Presented by Pavithra Eswaramoorthy_

### Notes

- A line plot: add texture to the line, increase line width, block interactions.
- ALT Text: A 4 level framework to describe the visual/ plot.

---

## Driving Trust and Addressing Ethical Challenges in Transportation through Explainable AI
### _Presented by Natalie Beyer_

### Notes

* **Case Study**: Practical application in public transportation planning (tram systems)
* **XAI Definition**: Explainable AI - making AI decisions transparent and understandable

* **Key Questions Raised**:
  * How will AI affect knowledge acquisition in future generations?
  * Does simplifying complex systems for explanation risk inaccuracy?
  * Can we be confident that all relevant factors are being considered?

---

## Information Retrieval Without Feeling Lucky: The Art and Science of Search
### _Presented by Anja Pilz_

### Notes

* **Core Concept**:
  * Search is about finding usable information, not just data

* **Precision Metrics**:
  * Discounted Cumulative Gain (DCG):
    - Weighted ranking where 1st result has highest importance
    - Each subsequent result (2nd, 3rd, etc.) carries decreasing weight
  * Measurement Methods:
    - Requires human(-level) evaluation for accuracy
    - Click-through rate (CTR) helps identify low-precision queries

* **Recall Strategies**:
  * Evaluation Methods:
    - Verify needed results appear in result set
    - Identify when result sets are too small
  
* **Query Optimization Techniques**:
  * Query Relaxation: Remove specificity to broaden results
  * Query Expansion: Add terms to increase coverage
  * Key Difference: Relaxation reduces constraints while expansion adds alternatives

---

## Reasonable AI
### _Presented by Kristian Kersting_

### Notes

* **Key Questions**:
  * Does model size truly matter in AI development?
  * How can AI positively challenge societal norms?

* **AI Recognition**:
  * Two Nobel prizes awarded to AI pioneers in 2024
  * Growing importance of open source AI ecosystems

* **European Perspective**:
  * Need for open discussion on European values in AI
  * AI encompasses both data and algorithmic components

* **Core Conclusions**:
  * Short-term: "Bigger is Better" approach shows value
  * Long-term: New paradigms necessary for sustainable AI
  * RAI (Reasonable AI) as a balanced framework

* **Human-AI Integration**:
  * AI augmented with human reasoning capabilities
  * Parallels to Kahneman's System 1 and System 2 thinking

* **Ethical Considerations**:
  * Who determines ideal outcomes in AI systems?
  * Ontological logic for ethical decision-making
  * Restrictions needed for certain AI applications (e.g., image generation)

---

## AI Coding agent - what is it, how it works and is it good for developers
### _Presented by Cheuk Ting Ho_

### Notes

* **Key Terms**:
  * **Junie**: Jetbrains AI coding agent
  * **AI Agent Definition**: Designed to interact with environment

* **AI Agent Characteristics**:
  * Data collection capabilities
  * Task performance abilities
  * Independent action selection
  * Examples: Customer support chatbots, AI coding agents, medical helpers

* **AI Agent Process Flow**:
  * Reasoning about situations
  * Understanding assigned tasks
  * Plan/solution development
  * Plan/solution execution
  * Result evaluation and feedback

* **Workflow Stages**:
  * Scene setting
  * Action plan generation
  * Action plan execution
  * Result evaluation

* **Key concerns**:
  * Data privacy
  * Data is send through LLM's

---

## Beyond Agents: What AI Strategy Really Needs in 2025
### _Presented by Alexander CS Hendorf_

### Notes

* **Why I joined NVIDIA GTC**:
  * Get Diverse AI Applications Across Industries
  * Deeper Insights into Ai Agents.
  * AI and Misapplied AI fatigue
* **What is GTC**:
  * Graphics Technology Conference
  * AI Models & Intelligent Systems
  * Digital Twins
  * Developer Tools
  * Applied AI & Soietal Impact
* **Conference takeaways**:
  * AI is Everywhere and in Every Thing
  * Agents are everywhere
  * Agentic AI is everywhere
  * And this means NOT only in software environments
  * Synthetic Data
  * Simulation
  * Digital Twins (are back)
  * Useful robots
  * Autonomous Robots
  * Everything Runs on Open Source
  * Shrunk data centers to AI Factories with less energy consumption
* **Strategic Pattern: Convergence**:
  * AI no longer siloed in domains
  * Innovation happens in intersections of domains