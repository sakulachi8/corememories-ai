# CoreMemories — AI-Powered Living Legacy Platform

<img width="500" height="500" alt="Kcube_Core_Memory_AI" src="https://github.com/user-attachments/assets/00239984-bff4-451d-bb7c-dd014234587e" />


---

## Overview
CoreMemories is a next-generation **legacy-preservation platform** that transforms personal stories into **living conversations**. Using Conversational Memory AI and a secure Memory Vault, individuals can preserve their **voice, wisdom, and presence**, ensuring loved ones stay connected across generations.

---

## Problem Statement
Families and individuals faced limitations when preserving legacies:
1. Memories reduced to static photos or text without authentic voices.
2. No way for future generations to ask questions or receive advice.
3. Lack of a secure, unified system to preserve and enrich stories over time.

The challenge was to design a platform that creates **interactive, secure, and emotionally meaningful legacies**.

---

## Solution
Kcube AI developed **CoreMemories**, a platform blending **AI voice replication**, **conversational intelligence**, and **multimedia enrichment** into one seamless system.

### Key Features
- **Conversational Memory AI** — interactive conversations with loved ones’ authentic voices.  
- **Memory Vault** — private, encrypted repository for memories, recordings, and media.  
- **AI Voice Replication** — captures unique tone, personality, and laughter.  
- **Family Collaboration** — relatives can co-build legacies with prompts & shared memories.  
- **Multimedia Enrichment** — add photos, videos, and social content.  
- **Flexible Plans** — individual, family, and extended family tiers.  

---

## Tech Stack
| Technology                       | Purpose                              |
| -------------------------------- | ------------------------------------ |
| **FastAPI**                      | Scalable backend and API services    |
| **React**                        | Modern, responsive user interface    |
| **PostgreSQL**                   | Secure structured data storage       |
| **OpenAI**                       | Conversational AI & Embedding Models |
| **Voice AI Models (ElevenLabs)** | Custom voice training & replication  |
| **Azure Cloud**                  | Enterprise-grade hosting & security  |

---

## User Flow Diagram

```mermaid
sequenceDiagram
    participant User as User
    participant Vault as Memory Vault
    participant VoiceAI as Voice Replication Model
    participant ChatAI as Conversational AI
    participant Media as Photos/Videos
    participant Family as Family & Friends

    User->>Vault: Share stories & upload media
    User->>VoiceAI: Record script for voice learning
    Vault-->>ChatAI: Provide stored memories for conversation
    ChatAI-->>Family: Deliver interactive conversations
    Media-->>Vault: Enrich stories with visuals
    Family->>Vault: Suggest prompts & new questions
    Vault-->>User: Notify about new memory prompts

```

---

## Live Link
[🌐 Core Memories AI](https://corememories.ai/)

---

**Developed by [Kcube AI](https://kcube.ai)**  
*AI Engineered for Excellence*
