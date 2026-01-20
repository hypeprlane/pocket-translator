Part 1: Dataset Engineering for Translation Models
- Designing the 3M example corpus structure (long-form, short, instruction-preserving)
- Any-to-any language pair coverage strategy (20 directions, not just EN↔X)
- Synthetic data generation pipeline with hostel LLMs (for bugdet)
- Data quality filtering and deduplication
 
Part 2: Evaluation Before You Train
- Building the LLM-as-judge framework
- Designing head-to-head comparison methodology
- Statistical significance with 96K comparisons
- Baseline benchmarking against existing models
 
Part 3: SFT on LFM2.5 Architecture
- LFM architecture primer (state-space + attention hybrid)
- Training setup, hyperparameters, hardware requirements
- Instruction-following preservation during translation fine-tuning
- Checkpoint selection strategy
P
art 4: DPO Refinement — The 1% That Gets You 10%
- Curating the 30K preference pairs
- Selecting "preferred" vs "rejected" translations
- DPO hyperparameters and training dynamics
- Before/after comparison

Part 5: iOS Deployment with CoreML or with ExecuTorch (latest tutorial from Unsloth)
- Model conversion pipeline (PyTorch → CoreML)
- Quantization strategies for 1.2B on device
- Memory management and inference optimization
- Building the Swift wrapper
