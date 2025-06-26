# 📞 Enhanced Pipecat Phone Chatbot with Intelligent Call Management

This repository extends [Pipecat's Phone Chatbot example](https://github.com/pipecat-ai/pipecat/tree/main/examples/phone-chatbot) with enhanced call management features including silence detection, graceful call termination, and post-call analytics.

## 🎥 Demo Video

[Watch the demo in action](https://www.loom.com/share/7cd8f496d9cc4390a6368efe7b7219c0?sid=2578c1ea-5f30-44c7-9d6e-81b386509a07)

## 🚀 What This Extension Adds

Building on Pipecat's excellent phone chatbot foundation, this extension implements:

- **🔇 Intelligent Silence Detection** – Plays TTS prompts after 10+ seconds of silence to keep conversations flowing
- **🔚 Graceful Call Termination** – Automatically ends calls after 3 unanswered prompts to prevent indefinite connections
- **📊 Post-Call Analytics** – Logs comprehensive call statistics including duration, silence events, and engagement metrics
- **📲 Inbound Call Support** – Works locally or via ngrok for testing and development

## 🙏 Credits

This project is built on top of the amazing work by the [Pipecat team](https://github.com/pipecat-ai/pipecat).

**Pipecat** is an open-source Python framework for building real-time voice and multimodal conversational agents. It orchestrates audio, AI services, different transports, and conversation pipelines effortlessly—allowing developers to focus on what makes their agent unique.

### Key Pipecat Features Used:

- Real-time voice processing and conversation handling
- Speech-to-text and text-to-speech integration
- Pluggable AI services architecture
- WebRTC transport for phone connectivity
- Ultra-low latency interaction capabilities

## 🛠️ Problem Statement Addressed

This extension was created to solve common challenges in phone-based AI agents:

1. **Silent Call Management** – Handling situations where callers don't respond
2. **Resource Optimization** – Preventing calls from running indefinitely
3. **Call Analytics** – Understanding conversation patterns and engagement
4. **User Experience** – Providing smooth, natural conversation flow

## 🔧 Technical Implementation

The enhancements include:

- **Silence Detection Engine** – Monitors audio input for extended quiet periods
- **Prompt Management System** – Tracks and manages TTS prompts during silence
- **Call State Management** – Handles graceful disconnection logic
- **Analytics Logger** – Captures and stores call metrics for analysis

## 📚 Getting Started

1. Follow the original [Pipecat Phone Chatbot setup](https://github.com/pipecat-ai/pipecat/tree/main/examples/phone-chatbot)
2. Install additional dependencies for this extension
3. Configure your environment variables for enhanced features
4. Run locally or deploy with ngrok for inbound call testing

### 🚀 Main Implementation

The enhanced phone chatbot implementation can be found here:
**[📁 simple_dialin.py](examples/phone-chatbot/simple_dialin.py)** - Main bot file with silence detection and call management features

## 🌟 Why Pipecat?

Pipecat provides the perfect foundation for voice AI applications with:

- **Voice-first Architecture** – Built specifically for real-time voice interactions
- **Modular Design** – Easy to extend and customize for specific use cases
- **Production Ready** – Handles the complex orchestration of AI services
- **Active Community** – Continuous development and support

## 📞 Original Pipecat Resources

- **Main Repository**: [pipecat-ai/pipecat](https://github.com/pipecat-ai/pipecat)
- **Documentation**: [docs.pipecat.ai](https://docs.pipecat.ai)
- **Discord Community**: [Join the conversation](https://discord.gg/pipecat)
- **Phone Chatbot Example**: [Original implementation](https://github.com/pipecat-ai/pipecat/tree/main/examples/phone-chatbot)

---

_This extension demonstrates the power and flexibility of the Pipecat framework for building sophisticated voice AI applications. Special thanks to the Pipecat team for creating such an excellent foundation for real-time conversational AI._
