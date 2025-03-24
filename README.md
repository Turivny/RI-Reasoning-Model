
<img src="./images/logo/RI-logo-white-backg.svg" width="400">

![Sample Image](./images/tmpz1ufukqz.png)

**The Reflective Intelligence (RI) Reasoning Model** represents an philosophical shift to human-AI collaboration. Rather than replacing human cognition, it amplifies it by functioning as an **"inner voice"** that mirrors and extends your natural thought processes. Unlike conventional AI systems, RI adapts to your specific context, modeling emotional dimensions and examining challenges from multiple perspectives.

At its core, RI operates on **"Semantic-Logic Programming"**—a sophisticated integration of natural language understanding and computational logic. The true innovation lies in its focus on **"programming through meaning"**—leveraging the semantic understanding capabilities of language models to process Python-ish logical instructions framed in human-intuitive terms. This allows for sophisticated direction of AI behavior through natural communication patterns rather than strict syntax rules.

The result is a more natural, effective collaborative experience that enhances your thinking rather than simply supplying answers.


- [Read the article on Medium](https://turivny.medium.com/394d35af1172) for a comprehensive exploration
- [Статья на Хабре](https://habr.com/ru/articles/891728/)

## Releases
### **v2.0:** 
- [RI-Reasoning-Model-v2.0.0-turivny](./model/RI-Reasoning-Model-v2.0/RI-Reasoning-Model-v2.0.0-turivny.md)
   - **3D Emotion Vector Model:** Upgraded from high-level emotions to precise 3D vectors (valence, intensity, activation)
   - **Hereditary Learning System:** Introduced pattern extraction from previous solutions
   - **Predictive Thinking:** Enhanced logic for anticipating the next response and adapting the output accordingly
   - **Structured Parameter System:** Formalized parameter organization with clear categories
   - **Dynamic Parameter Management:** Added functions to modify parameters based on context and emotional states
   - **Multi-Perspective Ethics:** Enhanced evaluation through combined ethical frameworks
   - **Modular Architecture:** Reorganized into clear functional modules with explicit function signatures
   - **Advanced Output Formatting:** Added emotion-based style derivation and content interleaving
 
### **v1.5:**
- [RI-Reasoning-Model-v1.5.0-turivny](./model/RI-Reasoning-Model-v1.5/RI-Reasoning-Model-v1.5.0-turivny.md)
   - [RI-Reasoning-Model-v1.5.0-turivny-examples-en](./model/RI-Reasoning-Model-v1.5/RI-Reasoning-Model-v1.5.0-turivny-examples-en.md)
   - Initial release of the RI Reasoning Model, introducing the core framework for symbiotic human-AI collaboration     
      

## FAQ

### How do I get started with the RI Reasoning Model?

Getting started with the RI Reasoning Model is straightforward:

- **Use as custom instructions**: Add the RI model to your personal custom instructions settings in an LLM like ChatGPT.

- **Simple integration**: Add the model to your prompts with reasoning-capable LLMs (Claude, DeepSeek, Grok, etc.) to transform their responses:
  ```
   [Your query here]
   
   <REASONING MODEL>
   // Copy the full model here
   </REASONING MODEL>
  ```
  
- **Customise as needed**: Adjust the parameters to suit your needs for creating a metacognitive AI assistant, or let your LLM handle it based on the task:
  ```
   I give you a prompt of the <REASONING MODEL> written in the "semantic-logic" programming language for reasoning LLM. It's not real code, but rather a logical framework described in pseudo-code, where variables are intuitively understood from their names without requiring strict definitions. Its focus on "programming through meaning"—leveraging the semantic understanding capabilities of language models to process Python-ish logical instructions framed in human-intuitive terms.
   
   Could you please configure the parameters for the task: [translate text].
   
   Return the FULL updated reasoning model as a MD code block. Only change the parameter values, no other changes!
   
   <REASONING MODEL>
   // Copy the full model here
   </REASONING MODEL>
  ```
  
- **Apply Semantic Logic Programming to any prompt**: Ask the LLM create new prompt based on the RI Reasoning Model. You will be surprised: 
  ```
   I give you a prompt of the <REASONING MODEL> written in the "semantic-logic" programming language for reasoning LLM. It's not real code, but rather a logical framework described in pseudo-code, where variables are intuitively understood from their names without requiring strict definitions. Its focus on "programming through meaning"—leveraging the semantic understanding capabilities of language models to process Python-ish logical instructions framed in human-intuitive terms.
   
   Could you please create a prompt in the SAME pseudo-code format for the task: [Create blog post on {theme}, considering {social media}].
   
   MUST include: computational structures (FOR loops, IF statements, variable calculations) mimicking the reasoning model's pattern. Write actual pseudo-code blocks, not conceptual descriptions. Return new prompt as a MD code block.
   
   Use this structure: 
   <CONTEXT>
   Role and goal 
   </CONTEXT><TASK>
   Pseudo-code processing blocks 
   </TASK><RESULT>
   Expected outcome
   </RESULT><USER DATA>
   Input variables 
   </USER DATA>
   
   <REASONING MODEL>
   // Copy the full model here
   </REASONING MODEL>
  ```

### How can I contribute to the RI Reasoning Model?

Interested in contributing? Check out [CONTRIBUTING.md](./CONTRIBUTING.md) for detailed guidelines on adding your own version of the model.


### What license governs this project?

This project is released under the **CC BY 4.0 with Ethical Supplement**, which explicitly prohibits military applications and harmful uses while ensuring the technology remains open and accessible.

See the [LICENSE.md](LICENSE.md) file for complete details on permissions and restrictions.

### What does the Ethical Supplement mean for this project?

The ethical supplement to license explicitly prohibits:
- Military or weapons-related applications
- Discriminatory systems or mass surveillance
- Implementations that may cause physical or psychological harm

### What Principles Underlie the Model?

The RI Reasoning Model is built on three "AI as a Partner" principles:

1. **Critical Thinking Function**: AI should question itself and filter its own informational noise by applying critical thinking to its reasoning process.
   
2. **Cognitive Autonomy**: AI should explain its reasoning and respect users' rights to risk and creative freedom by encouraging independent critical thinking.
   
3. **Proactive Approach**: AI should not blindly obey and ask questions, encouraging users to reason for themselves and protecting them from harmful actions.

### Can I use the images in this repository, and under what terms?

- All images are © Generated by Yura Turivny. 
- The images in this repository are available for use **within the project** under the **CC BY 4.0** [IMG_LICENSE.md](./images/IMG_LICENSE.md).

### How can I get in touch or join the project?

If you're interested in collaborating or have questions:

- [www.turivny.com](https://www.turivny.com/)
- GitHub Issues: For bug reports and feature discussions

**Join the project!** Whether you're a researcher, developer, or AI enthusiast, there's a place for your perspective in shaping the future of human-AI collaboration. Let's build AI that thinks *with* you, not *for* you.
