# DS2ST-LM (Timbre-Aware LLM-based Direct Speech-to-Speech Translation Extendable to Multiple Language Pairs)
Direct Speech-to-Speech Translation System with LLM (DS$2$ST-LM) is a scalable, single-stage direct S$2$ST framework that leverages the language understanding capabilities of LLMs. DS$2$ST-LM integrates a speech encoder, an  LLM, and a neural vocoder.
The main contributions of this work are summarized as follows:
* We propose DS$2$ST-LM, a single-stage, LLM-based direct S$2$ST framework, and demonstrate its effectiveness across multiple language pairs.
* We construct and publicly release the GigaS$2$S-$1000$ dataset, enabling large-scale research on direct S$2$ST.
* We systematically evaluate three projection architectures: Linear, Conv$1$D–Linear, and Q-Former, and analyze their effects on convergence stability and translation quality.
* We investigate semantic token generation from target speech versus target text and analyze their impact on direct S$2$ST translation performance.
* We integrate timbre-aware speech synthesis into direct S$2$ST by conditioning on semantic tokens and a reference speaker prompt to synthesize speaker-specific target speech.
