<p align="center">
    <img src="https://raw.githubusercontent.com/WilliamBUG/Assistant-Zero/main/assets/az-logo.png" width="300"/>
<p>

    
## 🔔 Progress Update (May 2025)

We have successfully released the **initial checkpoint** of the **Assistant-Zero** project, prepared for the next phase of reinforcement learning. This stage focuses on visual agent training via a complete pipeline—ranging from data generation to supervised fine-tuning in simulation environments. This checkpoint also serves as the evaluation baseline for our reinforcement learning framework and acts as the initialization point for subsequent reinforcement learning stages. We have built a full Android-based evaluation pipeline and conducted initial experiments on [Android World](https://github.com/google-research/android_world) and [Android Control](https://github.com/google-research/google-research/tree/master/android_control) tasks. The first checkpoint is now available on [Hugging Face](https://huggingface.co/infly/INF-AZ-7B-0524). These results demonstrate the effectiveness of our data augmentation and training strategies for function-capable visual agents.


---


# Assistant-Zero: Pioneering the Future of Personal AI Assistants

## 1. Welcome to Assistant-Zero! 🚀  
The world of large language models (LLMs) and multimodal AI has exploded with incredible advancements. Tools like ChatGPT and Claude have become must-have assistants, seamlessly blending into our daily work and lives. Most personal AI assistants today rely on cloud-based APIs to tap into massive models—mainly because running ultra-large-scale models efficiently on local devices is still a tough nut to crack. But with the rise of open-source models like DeepSeek, Llama, and Qwen, plus breakthroughs in AI hardware, we can’t help but dream: *What’s the ultimate form of a personal intelligent assistant?*

That’s where **Assistant-Zero** comes in! 🎉 Our mission is to explore and build the tech stack for the **ultimate personal AI assistant**. We’re diving into the future head-first—developing cutting-edge model techniques and collaborating with the community to shape the next generation of personal assistants. 

<p align="center">
    <img src="https://raw.githubusercontent.com/WilliamBUG/Assistant-Zero/main/assets/az_style.webp" width="60%"/>
<p>

## 2. Our Vision for the Ultimate Personal Assistant 👀

As of today (February 22, 2025), our team is convinced that the *ultimate personal intelligent assistant*:  

- **What it is:** The closest, most personal assistant right by your side. 🤝 
- **Where it lives:** Your smartphone and the next wave of cutting-edge AI mobile devices. 📱 
- **Core Models:** powered by **On-device Vision-Language Models (VLMs)**. 🌟

Here’s why we’re so excited about this: while massive models are evolving fast, we believe the future hinges on a key realization—*your personal data matters*. With growing concerns about security, rapid advancements in AI hardware, and open-source smaller-scale models (~30B) delivering increasingly impressive results, the endgame is clear: the future personal assistant will be an **on-device AI companion**. Drawing from our team’s deep understanding of LLMs tech stacks—and the trend toward streamlined, end-to-end algorithms and system design—we’re betting big on a **VLM** as the heart of this revolution.  ❤️ 

### The Challenge? Hardware’s Playing Catch-Up ⚡   
Right now, the biggest hurdle is that hardware speeds can’t quite keep pace with model ambitions. Today’s most powerful models are still too hefty for local deployment. But if history’s taught us anything, it’s that graphics cards and personal devices evolve at lightning speed. We’re talking a massive leap forward in the next 1-3 years—think next-gen upgrades with specialized AI chips built from the ground up for this kind of magic. The future’s coming fast, and we’re here to build it!

## 3. What Powers Assistant-Zero? Our Model’s Must-Have Features 💡

We’re dreaming big for Assistant-Zero, and here’s what we believe the ultimate on-device assistant *needs* to rock:

### (1) Seamless Function Calling – Tools at Your Fingertips 🛠️  
The top priority? A slick **function call capability** that taps into device-side tools to get stuff done. This could be *the* game-changer for the future! We’re on a mission to dig into every existing function call or agent approach with VLMs and explore how to hook up external tools like pros. Let’s make it happen—smooth, fast, and flawless.

### (2) Killer Summarization Skills – Your Info Superpower 📝  
Imagine an assistant that can **summarize anything** based on context and deliver spot-on answers. Why does this matter?  
- **Efficiency Boost:** In a world drowning in info overload, summing things up saves time and turbocharges productivity.  
- **Problem-Solving Muscle:** Post-function call, it’s the real-deal ability to tackle issues head-on.  
We’re talking next-level clarity in a snap—who doesn’t want that? ✨

### (3) Router Smarts – The Brain Behind the Operation 🧠  
Here’s where it gets clever: **router capability**. Picture this—an assistant that sizes up a problem’s difficulty, then dishes it out to the right online model or platform for the win. With a flood of AI models in the future, your on-device assistant becomes the ultimate gatekeeper. No more “which tool do I use?” stress—it’s got your back, acting as a smart router.  
- Think of it as function calling evolved: not just *can it call the right tool?*, but *does it get your intent?* It’ll even know its limits and call for backup when needed. Teamwork makes the dream work! 🌟

### (4) The Secret Sauce? Personalization 🎨  
All these hardcore features? They’re getting a **personalized twist** as the killer selling point of *ultimate personal intelligent assistant*. This isn’t just an assistant—it’s *your* assistant, tailored to you, your vibe, and your needs. Because the future isn’t one-size-fits-all—it’s uniquely yours.

# 📍 **Assistant-Zero Roadmap** 

In the first stage, we investigate the function-calling capability of VLMs and train the visual agent through reinforcement learning. 

### 📌 **Stage 1: Visual Agent (Q1-Q2 2025)**

- ✅ Build offline eval pipeline (Android control + AITZ + multimodal tasks)  
- ✅ Debug the training framework, and run the first batch.  
- ✅ Set up + debug the Android World framework. 
- ✅ Develop agents for online interaction experiments. 
- ✅ Design algorithm + produce data. 
- ✅ Test VLMs with SFT for function calls.
- ⬜ Test VLMs with RL for function calls.
- ⬜ ~~Quantize + deploy to phones~~ (require further system research and adaptation)
- ⬜ Open source preparation

---

### What’s Next? The Sky’s the Limit! ☁️
- Summarization and rooter: exploring the next key features.
- Scale up with personalization: More apps, more tasks, more personalization.  
- Open-source the eval pipeline and our agent design framework—let’s grow this together!


# 🌟 **Contributors**  

**Assistant-Zero** project is currently supported by several researchers and engineers with passion to the *on-device ultimate personal intelligent assistant*. 

🛠 All contributors have **contributed equally** to the development and progress of **Assistant-Zero**. Contributions are listed in no particular order.

- 👨‍💻 **Tan Xiaoyu** – Project Lead, Agent Design, Training
- 👨‍💻 **Qu Chao** – Algorithm Design, Training
- 👨‍💻 **Hao Jiaran** - Evaluation, Agent Design, Simulation
- 👨‍💻 **Yao Tianchu** - Data Pipeline, Training
- 👨‍💻 **Lu Dakuan** - Evaluation
- 👨‍💻 **Hu Hongqing** - Model Quantization, Deployment
- 👨‍💻 **Songliu Yihan** - Training
- 👨‍💻 **Wei Lingfeng** - Inference, Android Simulation
- 👨‍💻 **Ai Xi** - Technical Support

