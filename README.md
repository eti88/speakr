<div align="center">
    <img src="static/img/icon-32x32.png" alt="Speakr Logo" width="32"/>
</div>

<h1 align="center">Speakr</h1>
<p align="center">Self-hosted, intelligent note-taking for meetings and recordings</p>

<p align="center">
  <a href="https://www.gnu.org/licenses/agpl-3.0"><img alt="AGPL v3" src="https://img.shields.io/badge/License-AGPL_v3-blue.svg"></a>
  <a href="https://github.com/murtaza-nasir/speakr/actions/workflows/docker-publish.yml"><img alt="Docker Build" src="https://github.com/murtaza-nasir/speakr/actions/workflows/docker-publish.yml/badge.svg"></a>
</p>

> Speakr is an intelligent, self-hosted web application that transforms your audio recordings into organized, searchable, and insightful notes. By running on your own server, it ensures your sensitive conversations and data remain completely private.

> Designed for a wide range of uses, Speakr is trusted by professionals for meeting minutes, by therapists for session notes, by students for lecture capture, and even for transcribing D&D sessions. It automatically transcribes audio with speaker identification, generates concise summaries, and provides an AI chat interface to interact with your content.

<div align="center">
    <img src="static/img/main.png" alt="Speakr Main Interface" width="750"/>
</div>

---

## What's New?

###  Latest Release (Version 0.5.1)
* **Inquire Mode (Experimental):** Revolutionary AI-powered search across all your recordings! Ask questions like "What decisions were made about the marketing budget?" and get intelligent answers with context from relevant conversations. Perfect for finding insights across multiple meetings, interviews, or sessions.
* **Advanced Tagging System:** Organize recordings with multiple tags, each with custom summarization prompts and ASR defaults
* **Enhanced ASR Integration:** Configure language and speaker detection directly from the UI with automatic participant extraction
* **Word Document Export:** Download summaries and notes as beautifully formatted .docx files
* **Tag-based Search:** Filter recordings instantly using tags (e.g., `tag:meeting date:2025`)
* **Improved UI:** Better theme consistency, reorganized layouts with icons, and compact responsive design
* **Configurable Processing:** Respect chunk size settings and improved audio format handling

<details>
<summary><strong>Previous Version History</strong></summary>

### Version 0.4.2
* **Large File Chunking Support:** Automatically splits large audio files to work with transcription services that have file size limits (e.g., OpenAI's 25MB limit)
* **Optimized File Processing:** Improved efficiency by minimizing file conversions and using compressed formats
* **Enhanced Security:** Strengthened CSRF protection and fixed session timeout issues
* **Improved Recording Reliability:** Addressed several bugs related to in-browser recording

### Version 0.4.1 
* **Secure Sharing System:** Share transcriptions via public links with customizable permissions
* **Enhanced Recording & Note-Taking:** Redesigned recording interface with a real-time notepad
* **Advanced Speaker Diarization:** AI-powered speaker detection and saved speaker profiles
* **"Black hole" Directory:** Feature for automatic, hands-free audio file processing
* **Transcript Editing:** Manually edit and correct transcriptions
* **Clickable Timestamps:** Navigate audio by clicking timestamps in the transcript
* **Streaming Chat Responses:** More interactive and responsive AI chat

</details>

---
## Screenshots


<table align="center" style="width:100%;" border="0" cellpadding="10" cellspacing="0">
  <tr>
    <td align="center" width="50%">
      <img src="static/img/main2.png" alt="Main" width="90%"/>
    </td>
    <td align="center" width="50%">
      <img src="static/img/multilingual-support.png" alt="Multilingual" width="90%"/>
    </td>
  </tr>
</table>

---
<details><summary><strong>Transcription & chat</strong></summary>
<p align="center">
  <img src="static/img/transcription-chat-bubble-view.png" alt="Transcription and Chat" width="400"/>
  <br>
  <em>Integrated Chat</em>
</p>
</details>
<details><summary><strong>Tag based custom summarization prompts (tags)</strong></summary>
<p align="center">
  <img src="static/img/tags.png" alt="Transcription and Chat" width="400"/>
  <br>
  <em>Create tags for different use-cases (meetings, gamenight, patient interview, etc.) for quick customized summaries</em>
</p></details>
<details><summary><strong>Light & dark</strong></summary>
<table align="center" style="width:100%;" border="0" cellpadding="10" cellspacing="0">
  <tr>
    <td align="center" width="50%">
      <img src="static/img/light-mode.png" alt="Light Mode" width="90%"/>
      <br><em>Light</em>
    </td>
    <td align="center" width="50%">
      <img src="static/img/dark-mode.png" alt="Dark Mode" width="90%"/>
      <br><em>Dark</em>
    </td>
  </tr>
</table>
</details>

<details><summary><strong>Transcription views</strong></summary>
<table align="center" style="width:100%;" border="0" cellpadding="10" cellspacing="0">
  <tr>
    <td align="center" width="50%">
      <img src="static/img/simple-transcription-view.png" alt="Simple View" width="90%"/>
      <br><em>Simple</em>
    </td>
    <td align="center" width="50%">
      <img src="static/img/transcription-bubble-view.png" alt="Bubble View" width="90%"/>
      <br><em>Bubble</em>
    </td>
  </tr>
</table>
</details>

<details><summary><strong>Speaker identification</strong></summary>
<table align="center" style="width:100%;" border="0" cellpadding="10" cellspacing="0">
  <tr>
    <td align="center" width="33%">
      <img src="static/img/intuitive-speaker-identification.png" alt="AI-assisted" width="90%"/>
      <br><em>AI-assisted</em>
    </td>
    <td align="center" width="33%">
      <img src="static/img/manual-auto-speaker-identification.png" alt="Manual & Auto" width="90%"/>
      <br><em>Manual & Auto</em>
    </td>
    <td align="center" width="33%">
      <img src="static/img/speaker-suggestions.png" alt="Suggestions" width="90%"/>
      <br><em>Saved Suggestions</em>
    </td>
  </tr>
</table>
</details>

<details><summary><strong>Recordings & notes</strong></summary>
<table align="center" style="width:100%;" border="0" cellpadding="10" cellspacing="0">
  <tr>
    <td align="center" width="33%">
      <img src="static/img/rec1.png" alt="Options" width="90%"/>
      <br><em>Recording Options</em>
    </td>
    <td align="center" width="33%">
      <img src="static/img/rec2.png" alt="Mic" width="90%"/>
      <br><em>Mic/System Audio</em>
    </td>
    <td align="center" width="33%">
      <img src="static/img/rec3.png" alt="Both" width="90%"/>
      <br><em>Mic + System Audio</em>
    </td>
  </tr>
</table>
</details>

---

## Core Features

* **Self-Hosted and Private:** Keep full control over your data by hosting Speakr on your own server.
* **Inquire Mode (Experimental):** Search and chat across all your recordings using AI-powered semantic search. Ask questions about any topic and get intelligent answers with relevant context from your entire audio library.
* **Advanced Transcription & Diarization:** Get accurate transcripts with optional AI-powered speaker identification (diarization) to know who said what.
* **AI-Powered Insights:** Automatically generate titles and summaries for your recordings. Use the integrated chat to ask questions and pull insights directly from the transcript.
* **Install as a PWA App:** Install on your phone for quick and easy recordings and note capture. 
* **Versatile Recording & Upload:** Upload existing audio files or record directly in the browser or PWA app. Capture audio from your microphone, your system's audio (e.g., for an online meeting), or both simultaneously.
* **Automated Processing:** Designate a "black hole" directory for drag-and-drop batch processing of audio files.
* **Secure Sharing:** Create shareable links for your transcripts with granular controls, allowing you to include or exclude summaries and notes.
* **Customizable AI:** Configure the specific AI models, API endpoints (compatible with OpenAI, OpenRouter, local models), and custom prompts for summarization and chat.
* **Multi-User Support:** Includes a complete user management system with an admin dashboard.

<table align="center" style="width:100%;" border="0" cellpadding="10" cellspacing="0">
  <tr>
    <td align="center" width="33%">
      <img src="static/img/rec1.png" alt="Transcription and Chat" width="90%"/>
    </td>
    <td align="center" width="33%">
      <img src="static/img/rec3.png" alt="Speaker Identification" width="90%"/>
    </td>
    <td align="center" width="33%">
      <img src="static/img/intuitive-speaker-identification.png" alt="Speaker Identification" width="90%"/>
    </td>
  </tr>
</table>

---

## Getting Started

The recommended setup method uses Docker, which is simple and fast.

<details>
<summary><strong>Easy Setup: Docker Compose (Recommended)</strong></summary>

You only need Docker installed for this method; you do not need to clone the repository.

1.  **Create `docker-compose.yml`**
    Create a file named `docker-compose.yml` and add the following content:
    ```yaml
    services:
      app:
        image: learnedmachine/speakr:latest
        container_name: speakr
        restart: unless-stopped
        ports:
          - "8899:8899"
        env_file:
          - .env
        volumes:
          - ./uploads:/data/uploads
          - ./instance:/data/instance
    ```

2.  **Create Configuration (`.env`) File**
    Create a file named `.env` in the same directory. Your configuration will depend on whether you need speaker identification (diarization).

    * **Option A: Standard Whisper API (No Speaker Diarization)**
        This is the simplest method and works with any OpenAI Whisper-compatible API (like OpenAI, OpenRouter, or local LLMs).

        ```dotenv
        # --- Text Generation Model (uses /chat/completions endpoint) ---
        TEXT_MODEL_BASE_URL=[https://openrouter.ai/api/v1](https://openrouter.ai/api/v1)
        TEXT_MODEL_API_KEY=your_openrouter_api_key
        TEXT_MODEL_NAME=openai/gpt-4o-mini

        # --- Transcription Service (uses /audio/transcriptions endpoint) ---
        TRANSCRIPTION_BASE_URL=[https://api.openai.com/v1](https://api.openai.com/v1)
        TRANSCRIPTION_API_KEY=your_openai_api_key
        WHISPER_MODEL=whisper-1
        
        # --- Large File Chunking (for endpoints with file size limits) ---
        ENABLE_CHUNKING=true
        CHUNK_LIMIT=20MB           # Size-based chunking (legacy CHUNK_SIZE_MB also works)
        # CHUNK_LIMIT=1200s        # Alternative: Duration-based chunking (20 minutes)

        # --- Application Settings ---
        ALLOW_REGISTRATION=false
        ADMIN_USERNAME=admin
        ADMIN_EMAIL=admin@example.com
        ADMIN_PASSWORD=changeme
        
        # --- Inquire Mode (Experimental - AI search across all recordings) ---
        # ENABLE_INQUIRE_MODE=true
        
        # --- Docker Settings ---
        SQLALCHEMY_DATABASE_URI=sqlite:////data/instance/transcriptions.db
        UPLOAD_FOLDER=/data/uploads
        ```

    * **Option B: ASR Webservice (With Speaker Diarization)**
        This method enables speaker identification but requires running a separate ASR webservice container. See the **Advanced Configuration** section below for details on setting up the ASR service.

        ```dotenv
        # --- Text Generation Model (uses /chat/completions endpoint) ---
        TEXT_MODEL_BASE_URL=[https://openrouter.ai/api/v1](https://openrouter.ai/api/v1)
        TEXT_MODEL_API_KEY=your_openrouter_api_key
        TEXT_MODEL_NAME=openai/gpt-4o-mini

        # --- Transcription Service (uses /asr endpoint) ---
        USE_ASR_ENDPOINT=true
        ASR_BASE_URL=http://your_asr_host:9000  # URL of your running ASR webservice
        # Speaker diarization is automatically enabled with ASR
        # Optional overrides (defaults shown):
        # ASR_MIN_SPEAKERS=1
        # ASR_MAX_SPEAKERS=5

        # --- Application Settings ---
        ALLOW_REGISTRATION=false
        ADMIN_USERNAME=admin
        ADMIN_EMAIL=admin@example.com
        ADMIN_PASSWORD=changeme
        
        # --- Inquire Mode (Experimental - AI search across all recordings) ---
        # ENABLE_INQUIRE_MODE=true
        
        # --- Docker Settings ---
        SQLALCHEMY_DATABASE_URI=sqlite:////data/instance/transcriptions.db
        UPLOAD_FOLDER=/data/uploads
        ```

3.  **Start the Application**
    After editing your `.env` file with your API keys and settings, run the following command:
    ```bash
    docker compose up -d
    ```
    Access the application at `http://localhost:8899`. The admin user will be created on the first run.

</details>

<details>
<summary><strong>Advanced Setup: Build from Source</strong></summary>

Follow these steps if you want to modify the code or build the Docker image yourself.

1.  **Clone the Repository:**
    ```bash
    git clone [https://github.com/murtaza-nasir/speakr.git](https://github.com/murtaza-nasir/speakr.git)
    cd speakr
    ```
2.  **Create Configuration Files:**
    Copy the example files. Use `config/env.whisper.example` for the standard API method or `config/env.asr.example` for the ASR webservice method.
    ```bash
    cp docker-compose.example.yml docker-compose.yml
    cp config/env.whisper.example .env # Or cp config/env.asr.example .env
    ```
    Edit the `.env` file with your custom settings and API keys.

3.  **Build and Start:**
    ```bash
    docker compose up -d --build
    ```
</details>

---

## Usage Guide

1.  **Login:** Access the application (e.g., `http://localhost:8899`) and log in. The admin account is created from the `.env` variables on the first launch.
2.  **Set Preferences (Recommended):** Navigate to your **Account** page to set your default language, customize the AI summarization prompt, and add professional context to improve chat results.
3.  **Add a Recording:**
    * **Upload:** Drag and drop an audio file onto the dashboard or use the **New Recording** page.
    * **Record:** Use the in-browser recorder. You can record your mic, system audio, or both. **Note:** To capture system audio (e.g., from a meeting), you must share a **browser tab** or your **entire screen** and ensure the **"Share audio"** checkbox is enabled.
    * **Automated:** If enabled, simply drop files into the monitored "black hole" directory.
4.  **Interact with Your Transcript:**
    * From the gallery, click a recording to view its details.
    * Read the transcript, listen to the audio, and review the AI-generated summary.
    * Edit metadata like titles and participants.
    * Use the **Chat** panel to ask questions about the content.
5.  **Identify Speakers (Diarization):**
    * If you used the ASR method with diarization enabled, click the **Identify Speakers** button.
    * In the modal, assign names to the detected speakers (e.g., `SPEAKER 00`, `SPEAKER 01`). You can use the **Auto Identify** feature to let the AI suggest names based on the conversation.
6.  **Use Inquire Mode (Experimental - optional):**
    * **Enable it first:** Uncomment `ENABLE_INQUIRE_MODE=true` in your `.env` file and restart the application
    * Click the **Inquire** button in the header to enter semantic search mode
    * Ask questions like "What were the main action items discussed?" or "Who mentioned the budget concerns?"
    * The AI will search across all your recordings and provide answers with relevant context
    * Use filters to search specific recordings, speakers, or date ranges
    * Perfect for finding insights across multiple meetings or discovering patterns in your conversations
---
<details>
<summary><strong>Advanced Tagging System</strong></summary>
Speakr's tagging system allows you to organize recordings and customize their processing with tag-specific prompts and settings. Tags can be assigned to recordings to categorize them (e.g., "Meeting", "Interview", "Legal", "Medical") and each tag can have its own custom summarization prompt and ASR defaults.

### Key Features

#### Custom Summarization Prompts
Each tag can have its own custom prompt that gets applied automatically when generating summaries. This is incredibly powerful for different use cases:
- **Legal depositions** need case synopsis and key issues
- **Medical consultations** need symptoms, diagnosis, and treatment plans  
- **Team meetings** need action items and decisions
- **Interviews** need candidate assessment and key qualifications

#### Combining Multiple Tags
You can assign multiple tags to a recording, and their custom prompts will be combined in priority order. For example:
- Tag 1: "Legal" - Adds legal formatting requirements
- Tag 2: "Deposition" - Adds deposition-specific sections
- Tag 3: "Urgent" - Adds priority flagging

The prompts are merged based on tag selection order, allowing you to build complex summarization workflows from modular tag components.

#### ASR Configuration per Tag
Tags can also define default settings for the ASR service:
- **Language**: Set a specific language for transcription (e.g., "Spanish" for all "Cliente" tagged recordings)
- **Speaker Count**: Define min/max speakers (e.g., exactly 2 speakers for "Interview" tags)

### Configuration Precedence

Settings are applied in this order (highest to lowest precedence):
1. **Upload Screen Advanced Options** - User's manual selections in the UI
2. **Tag Defaults** - Settings configured in the tag
3. **Environment Variables** - System-wide defaults from `.env` file
4. **Auto-detection** - ASR service's automatic detection

This hierarchy ensures flexibility while maintaining sensible defaults.

### Writing Effective Summarization Prompts

#### Best Practices
1. **Be Specific and Detailed**: Don't just ask for a "summary" - specify exactly what you want
2. **Provide Structure**: Define clear sections and formatting
3. **Include Examples**: Show the AI exactly how you want the output formatted
4. **Request Completeness**: Ask for "all important nuances" to avoid missing details

#### Example Prompts

**Legal Deposition Prompt:**
```
Summarize this transcript in extreme detail. Identify the key issues discussed. 
First, give me the case synopsis. Then give me the minutes. Then, give me the 
key issues discussed. Then, any key takeaways. Then, any next steps. Then, 
all important things that I didn't ask for but that need to be recorded. 
Make sure every important nuance is covered.

Example Format:
## Case: ABC vs XYZ
The case is about [brief description]. The synopsis is [detailed overview].

**Participants:**  
- [Name 1] - [Role]
- [Name 2] - [Role]

---
### Minutes

**1. Introduction and Overview:**
- [Participant] expressed [key point with full context]
- Discussion regarding [topic with specific details]

### Key Issues Discussed
1. **[Issue Title]:** [Comprehensive description with all nuances]
2. **[Issue Title]:** [Full details including participant positions]

### Key Takeaways
- [Specific, actionable takeaway with context]

### Next Steps
- [Concrete action item with responsible party and timeline]

### Additional Important Information
- [Any critical details not covered above]
```

**Meeting Minutes Prompt:**
```
Summarize this transcript in extreme detail. First, give me minutes. Then, 
give me the key issues discussed. Then, any key takeaways. Then, any next 
steps. Then, all important things that I didn't ask for but that need to be 
recorded. Make sure every important nuance is covered.

Example Format:
### Minutes

**Meeting Participants:**  
- [Name] - [Department/Role]
- [Name] - [Department/Role]

**Date:** [Meeting Date]
**Duration:** [Length]

---

**1. Introduction and Overview:**
- [Participant] opened the meeting by [specific details]
- Key objectives outlined: [list each]

**2. [Topic Name]:**
- [Participant] presented [detailed summary of presentation]
- Discussion points raised:
  • [Specific point with who raised it]
  • [Counter-arguments or agreements]
- Decision reached: [Exact decision with rationale]

### Key Issues Discussed
1. **[Issue]:** [Complete description with all perspectives presented]
2. **[Issue]:** [Full context including constraints and opportunities]

### Key Takeaways
- [Specific conclusion with supporting details]
- [Important realization or learning]

### Next Steps
- [Action item] - Owner: [Name] - Due: [Date]
- [Action item] - Owner: [Name] - Due: [Date]

### Additional Notes
- [Any off-topic but important mentions]
- [Future considerations discussed]
```

#### Tips for Custom Prompts
- **Use consistent formatting** with markdown headers and bold text
- **Request specific information** relevant to your use case
- **Include participant identification** when speaker diarization is enabled
- **Ask for "all important nuances"** to ensure nothing is missed
- **Provide clear examples** of the desired output format
- **Structure sections logically** for easy scanning
- **Include catch-all sections** like "Additional Important Information"

### Setting Up Tags

1. **Create a Tag**: Go to Account Settings → Tag Management and create a new tag
2. **Configure Custom Prompt** (optional): Add your detailed summarization prompt
3. **Set ASR Defaults** (optional): Configure language and speaker settings
4. **Apply to Recordings**: Select tags when uploading or recording
5. **Combine Tags**: Select multiple tags to merge their prompts

Tags make Speakr very flexible, allowing you to maintain consistent formatting across similar recordings while adapting to different use cases with just a click.
</details>

---
<details>
<summary><strong>Advanced Configuration & Technical Details</strong></summary>

**For detailed deployment instructions and information about the various API's used, see the [Deployment Guide](DEPLOYMENT_GUIDE.md#configuration-options)**

The recommended method is to use the pre-built Docker image, which is fast and simple. This is explained above. 

## Automated File Processing

Speakr includes a powerful "black hole" directory monitoring feature that automatically processes audio files without manual uploads. This is perfect for batch processing scenarios where you want to drop files into a directory and have them automatically transcribed.

### How It Works

1. **File Monitoring:** Speakr monitors a designated directory for new audio files
2. **Automatic Detection:** When new audio files are detected, they are automatically queued for processing
3. **File Stability Check:** Files are checked for stability (not being written to) before processing
4. **Automatic Processing:** Files are moved to the uploads directory and processed using your configured transcription settings
5. **Database Integration:** Processed recordings appear in your gallery with the title "Auto-processed - [filename]"

**For detailed instructions on setting this up, see the [Deployment Guide](DEPLOYMENT_GUIDE.md#automated-file-processing-black-hole-directory)**

</details>

-----

## License

This project is **dual-licensed**:

1.  **GNU Affero General Public License v3.0 (AGPLv3)**
    [![License: AGPL v3](https://img.shields.io/badge/License-AGPL_v3-blue.svg)](https://www.gnu.org/licenses/agpl-3.0)

    Speakr is offered under the AGPLv3 as its open-source license. You are free to use, modify, and distribute this software under the terms of the AGPLv3. A key condition of the AGPLv3 is that if you run a modified version on a network server and provide access to it for others, you must also make the source code of your modified version available to those users under the AGPLv3.

    * You **must** create a file named `LICENSE` (or `COPYING`) in the root of your repository and paste the full text of the [GNU AGPLv3 license](https://www.gnu.org/licenses/agpl-3.0.txt) into it.
    * Read the full license text carefully to understand your rights and obligations.

2.  **Commercial License**

    For users or organizations who cannot or do not wish to comply with the terms of the AGPLv3 (for example, if you want to integrate Speakr into a proprietary commercial product or service without being obligated to share your modifications under AGPLv3), a separate commercial license is available.

    Please contact **speakr maintainers** for details on obtaining a commercial license.

**You must choose one of these licenses** under which to use, modify, or distribute this software. If you are using or distributing the software without a commercial license agreement, you must adhere to the terms of the AGPLv3.

## Roadmap

Speakr is in active development. Planned features include a faster way to switch transcription languages on the fly.

## Contributing

Feedback, bug reports, and feature suggestions are highly encouraged\! Please open an issue on the GitHub repository to share your thoughts.

**Note on Code Contributions:** Should the project begin formally accepting external code contributions, a Contributor License Agreement (CLA) will be required.
