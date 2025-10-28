# Bitshala BOSS Summit - Nostr Client Workshop

## Overview
This repository contains comprehensive documentation for building a Nostr client from scratch. The workshop provides hands-on experience with the Nostr protocol, teaching developers how to create a functional client that can connect to relays, manage keys, and interact with the decentralized network in real-time.

## What is Nostr?
Nostr (Notes and Other Stuff Transmitted by Relays) is a simple, open protocol that enables censorship-resistant global social networks. Unlike traditional platforms, Nostr uses:
- **Cryptographic keys** for identity (no centralized accounts)
- **Relay servers** for message distribution (no single point of failure)
- **Client applications** that users control (freedom to choose interfaces)

## Workshop Synopsis
This live coding session guides participants through building a **basic Nostr client from scratch**. You'll learn the fundamentals of the Nostr protocol while creating a working application that:
- Connects to multiple Nostr relays
- Generates cryptographic key pairs for identity
- Posts messages to the network
- Subscribes to and displays real-time feeds
- Provides a complete, take-home working client

## Core Content Structure

### Learning Objectives
- Understand Nostr protocol fundamentals (NIPs, relays, events)
- Master WebSocket connections to relay servers
- Implement cryptographic key management
- Build real-time message subscription systems
- Create a functional client interface

### What We'll Build
The workshop results in a working Nostr client with:
- **Relay Connection**: Connect to Nostr relays using WebSockets
- **Key Generation**: Create and manage nostr key pairs (nsec/npub)
- **Message Publishing**: Post signed events to the network
- **Feed Subscription**: Subscribe to and display real-time message feeds
- **User Interface**: Simple, functional client participants can customize

### Schedule Breakdown
The session flow:
- **Introduction**: Nostr protocol overview and architecture
- **Setup**: Development environment and dependencies
- **Live Coding Session 1**: Relay connections and event structure
- **Live Coding Session 2**: Key management and signing
- **Live Coding Session 3**: Publishing and subscribing to feeds
- **Testing & Debugging**: Hands-on experimentation
- **Q&A**: Discussion and next steps

## Prerequisites & Technical Requirements

### For Participants
- **Basic JavaScript knowledge**: Variables, functions, async/await
- **Code editor**: VSCode or similar installed on your system
- **Node.js**: Installed on your system (v14+ recommended)
- **Web browser**: Modern browser with developer tools

### Development Tools
- Text editor with syntax highlighting (like VSCode)
- Terminal/command line access
- (Optional) Git for version control

### No Prior Experience Required With
- Nostr protocol
- Cryptography
- WebSocket programming
- Decentralized systems


## Tech Stack
- **Frontend**: HTML, CSS, JavaScript
- **Runtime**: Node.js
- **Key Libraries**:
  - WebSocket API for relay connections
  - Native crypto APIs for key management
  - (Minimal dependencies for learning clarity)

## Key Concepts Covered

### Nostr Protocol Basics
- **Events**: Signed JSON objects that represent all data
- **Relays**: WebSocket servers that store and forward events
- **Keys**: Public/private key pairs for identity and signing
- **NIPs**: Nostr Implementation Possibilities (protocol standards)

### Technical Implementation
- WebSocket connection management
- Event creation and signing
- Subscription filters (REQ messages)
- Real-time data handling
- Client-relay communication patterns

## Learning Outcomes

By the end of this workshop, participants will:
- Understand the Nostr protocol architecture
- Know how to connect to and communicate with relays
- Be able to generate and manage cryptographic keys
- Have built a complete working Nostr client
- Understand event structure and signing
- Be equipped to build more complex Nostr applications
- Have a foundation for contributing to the Nostr ecosystem


## Getting Started

### Quick Start
1. Review this documentation to understand workshop objectives
2. Follow along during the live coding session
3. Experiment and customize your client after completion

### Post-Workshop
- Explore additional NIPs (Nostr Implementation Possibilities)
- Add features like user profiles, reactions, or DMs
- Connect to different relays
- Build mobile or desktop clients
- Contribute to the Nostr ecosystem

## Resources & Links

### Nostr Resources
- **Protocol Specification**: [NIPs Repository](https://github.com/nostr-protocol/nips)
- **Nostr.how**: Beginner-friendly guides and explanations
- **Nostr Relay List**: Find public relays to connect to
- **awesome-nostr**: Curated list of Nostr projects and resources

### Workshop Materials
- **Documentation**: This repository
- **Community**: Bitshala Discord server

### Further Learning
- Explore advanced NIPs (NIP-17 DMs, NIP-05 identification, NIP-42 auth)
- Study existing Nostr clients for patterns and ideas
- Join Nostr developer communities
- Build and share your own Nostr applications

## Support & Community

### During Workshop
- Ask questions during live session
- Work with fellow participants

### After Workshop
- **Bitshala Community**: Join the Discord for continued support
- **Nostr Developer Communities**: Connect with other builders
- **GitHub Issues**: Report documentation issues here

## Contributing

Found an issue or want to improve the documentation?
- Open an issue describing the problem or suggestion
- Submit a pull request with improvements
- Share your workshop experience and feedback

## License

This documentation and associated workshop materials are provided for educational purposes as part of the Bitshala BOSS Summit.

---

**Ready to build?** Start by setting up your development environment and following along with the live coding session. Happy coding!
