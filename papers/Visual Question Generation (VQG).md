### A Reinforcement Learning Framework for Natural Question Generation using Bi-discriminators


#### Overview:

This paper proposes a reinforcement learning framework for generating natural questions about images, known as Visual Question Generation (VQG). The approach focuses on two specific attributes of natural questions: content and linguistic quality. To address this, the authors introduce two discriminators, one for each attribute, inspired by adversarial learning. These discriminators guide the training process by providing scores used as rewards in the reinforcement learning framework. Experimental results on a standard VQG dataset demonstrate the effectiveness and robustness of the proposed model compared to state-of-the-art methods, both through automatic metrics and human evaluation. The paper suggests potential applications of the framework to other language generation tasks, such as dialogue generation with emotional content, and suggests avenues for future research, including improving efficiency in reward assignment and exploring collaborative methods for multiple discriminators.