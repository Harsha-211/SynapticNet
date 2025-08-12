# SynapticNet with NeuronGenesis 🧠

SynapticNet with NeuronGenesis is a **continual learning architecture** inspired by the brain’s ability to preserve past knowledge while learning new tasks.  
It prevents **catastrophic forgetting** by dividing the network into **task-specific neuron slices** and adaptively **growing new neurons** when needed.

---

## 📌 Key Features

- **Neuron Gating** – Activates only the neurons assigned to the current task.
- **Vertical Slicing** – Allocates fixed neuron segments for each task to avoid interference.
- **Freezing Mechanism** – Locks learned weights for old tasks to preserve knowledge.
- **NeuronGenesis** – Dynamically adds new neurons or layers when performance drops.
- **Multi-task Support** – Works with datasets like **MNIST**, **FashionMNIST**, **CIFAR-10**, and **CIFAR-100**.

---

## 🧪 Epperimental Results
- **Tested on** - MNIST and FashionMNIST
- **Training Strategy** - Each dataset was trained separately to simulate continual learning
- **Performance** - Achieved high accuracy on both datasets while maintaining previously learned task performance.

