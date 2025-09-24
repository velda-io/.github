<a href="https://velda.io">
    <img width="2334" height="1206" alt="Velda banner image" src="https://github.com/user-attachments/assets/31e8ba86-df2b-4be3-a43d-7b61d1a3b6f0" />
</a>

# Welcome to Velda

Velda is a cloud-native development, workload orchestration & HPC (High Performance Computing) platform. Directly scale your application from your development environment, no extra setup required.

## 🚀 What makes Velda special?

### Code on Velda
* **Seamless development experience** - Connect with your favorite IDE (SSH, VS Code, Cursor, Windsurf), or code directly from your browser
* **Instant onboarding** - Clone from pre-configured images or customize your own
* **Universal compatibility** - Works with most libraries, tools, and package managers
* **Persistent environments** - All customizations are saved and isolated per user

### Scale in seconds
* **Simple scaling** - Just prefix `vrun` to your command and run with requested resources
* **Run anything** - ML training, batch processing, microservice clusters
* **Unbounded capacity** - Access as many machines as you need from your cloud provider
* **Consistent environment** - Your code, data, dependencies always mounted on new machines

### Save money
* **No idle resources** - Only pay for what you use, no more idle GPUs or machines
* **Reduced engineering overhead** - Skip container image management
* **Optional K8s-free scaling** - Scale directly with VMs from your cloud provider

## 🏁 Quick Start

```bash
# Initialize mini-velda sandbox
velda mini init sandbox

# Connect to sandbox
ssh mini-velda

# Setup environment
sudo apt install python3
pip install torch

# Run workload with GPU
vrun -P aws:g6.xlarge train.sh
```

## 🤝 Join Our Community

We love contributions and community engagement! Here's how to get involved:

* 🌟 [Star us on GitHub](https://github.com/velda-io/velda)
* 👋 [Join our Discord community](https://discord.gg/MJQbeE33)
* 📜 [Read our blog posts](https://blog.velda.io)
* 🌐 [Learn more at velda.io](https://velda.io)

## 📚 Learn More

Check out our main repository [`velda-io/velda`](https://github.com/velda-io/velda) for detailed documentation, setup guides, and contribution guidelines.

---

*Ready to scale your development workflow? [Get started with Velda today!](https://velda.io)*