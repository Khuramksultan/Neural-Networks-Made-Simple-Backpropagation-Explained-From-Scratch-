# Neural-Networks-Made-Simple-Backpropagation-Explained-From-Scratch-

# Micrograd From Scratch — A Pakistani Student's Guide to Neural Networks 🇵🇰

> **"If you can't build it, you don't understand it."** — This is my attempt to truly understand neural networks by building micrograd from scratch, inspired by Andrej Karpathy's legendary tutorial.

## 🧠 What Is This?

This is my line-by-line implementation and explanation of **micrograd** — a tiny autograd engine that implements backpropagation on scalar values. While real deep learning frameworks work with massive matrices, micrograd strips away the complexity to show you the **soul of neural networks**.

## 🎯 Why I Built This

As a final-year CS student in Pakistan, I struggled to truly understand backpropagation. It always felt like magic. So I decided to:
- Watch Karpathy's video until it made sense
- Write every line of code myself
- Explain it in simple Urdu/Hinglish for Pakistani students
- Build visual intuitions for every concept

## 📚 What's Inside

| File | What It Does |
|------|--------------|
| `engine.py` | The autograd engine — each Value remembers its parents and knows how to backprop |
| `nn.py` | Neural network building blocks (Neuron, Layer, MLP) built on top of engine |
| `micrograd_guide.ipynb` | My step-by-step explanations with visuals |

