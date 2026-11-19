# Intelligent-Systems_CN_7050

I built MetalGuard, a computer vision prototype that inspects images of metal surfaces for cracks, holes, rust, and scratches. It checks image quality before inspection and lets users compare two approaches on the same image: Google Gemini’s vision API and a saved EfficientNet-B0 model. When the models disagree, MetalGuard explains why the case is on hold and routes it to a human reviewer.

I developed the dashboard in Python and Gradio, integrated n8n to track inspection events, and added a case-based AI chat so users can ask questions such as “Why was this surface flagged?” The project brought together model evaluation, workflow automation, and interface design around a practical quality-control problem.

Five skills to tag: Computer Vision · Python · Deep Learning · API Integration · Workflow Automation
