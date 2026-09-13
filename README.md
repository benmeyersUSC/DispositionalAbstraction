# Dispositional Abstraction

Ben Meyers's research into whether semantically equivalent prompts converge in
Jacobian-lens or J-space readouts earlier or more strongly than in raw activations.

## Start here

- [Collaboration rules](AGENTS.md): code ownership, documentation, and no Git commits.
- [Current project notes](PROJECT_NOTES.md): confirmed requirements, proposals,
  open decisions, and sources. Read this before resuming work.
- [First Qwen notebook](01_qwen_inference.ipynb): draft cells for Ben's line-by-line
  review and subsequent Colab execution.
- [Original handoff and correction memo](GPT_handoff.md): detailed research context.
- [J-Vision manuscript](J_Viz.pdf): exposition and research proposal; the correction
  memo has not yet been incorporated into the manuscript.

The first model is `Qwen/Qwen3-0.6B`, the post-trained instruction-following
checkpoint, using non-thinking prompt formatting. The current phase is notebook
review, with basic inference before activation hooks and Jacobians. The notebook
is written here and will be tested by Ben on Colab. No model has been downloaded
or executed by the assistant.
