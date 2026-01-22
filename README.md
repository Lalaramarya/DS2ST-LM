# DS2ST-LM (Timbre-Aware LLM-based Direct Speech-to-Speech Translation Extendable to Multiple Language Pairs)
Direct Speech-to-Speech Translation System with LLM (DS2ST-LM) is a scalable, single-stage direct S2ST framework that leverages the language understanding capabilities of LLMs. DS2ST-LM integrates a speech encoder, an  LLM, and a neural vocoder.
The main contributions of this work are summarized as follows:
* We propose DS2ST-LM, a single-stage, LLM-based direct S2ST framework, and demonstrate its effectiveness across multiple language pairs.
* We construct and publicly release the GigaS2S-1000 dataset, enabling large-scale research on direct S2ST.
* We systematically evaluate three projection architectures: Linear, Conv1D–Linear, and Q-Former, and analyze their effects on convergence stability and translation quality.
* We investigate semantic token generation from target speech versus target text and analyze their impact on direct S2ST translation performance.
* We integrate timbre-aware speech synthesis into direct S2ST by conditioning on semantic tokens and a reference speaker prompt to synthesize speaker-specific target speech.

  
![ds2stlm](https://github.com/user-attachments/assets/1dd5969f-4b2b-42d3-b515-e6d9e59ba33e)
