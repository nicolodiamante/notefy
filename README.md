<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github.com/nicolodiamante/notefy/assets/48920263/b834c045-97c4-4e48-a7ed-17f9b9bdd58a" draggable="false" ondragstart="return false;" alt="Notefy" title="Notefy" />
    <img src="https://github.com/nicolodiamante/notefy/assets/48920263/da5bee1b-8e5e-4225-b438-90cf537a61c9" draggable="false" ondragstart="return false; "alt="Notefy" title="Notefy" />
  </picture>
</p>

In an era where information overflows yet time remains scarce, Notefy aims to be an essential tool for efficient data management and processing. This shortcut integrates the intelligent conversation handling of [ChatGPT][chaGPT] with the precise audio transcription capabilities of [Whisper][whisper]. Notefy offers a new way to keep track of and process information amidst the deluge of meetings, lectures, and daily conversations. It skillfully converts spoken and written words into concise, organised summaries, transcending traditional note-taking methods. Notefy represents a transformative approach to processing and retaining information, serving a diverse range of users from professionals to students.

<br><br>

<p align="center">
  <picture>
    <img src="https://github.com/nicolodiamante/notefy/assets/48920263/a1227bd9-cea6-47f5-a430-88b4178c097c" draggable="false" ondragstart="return false; "alt="Siri + ChatGPT" title="Siri + ChatGPT" width="700px" />
  </picture>
</p>

<br><br>

Integrating Notefy with Siri is a straightforward process, but it does require meeting specific prerequisites and establishing certain links to ensure smooth functionality.
<br><br>

## Requirements to get Notefy to work

### Get the Shortcut

To start, ensure you have the [Apple Shortcuts][apple-shortcuts-download] app installed. Next, download the [Notefy][notefy-shortcut] Shortcut. You're welcome to rename the shortcut to a title that suits you. Before you begin using it, though, make sure you continue reading.

<br><br>

<p align="center">
  <a href="https://www.icloud.com/shortcuts/499c51a5d676459e87510fd7cf45e731" target="_blank">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://github.com/nicolodiamante/notefy/assets/48920263/39dc630c-36c5-4db4-b355-22f2eb5cf6d9" draggable="false" ondragstart="return false;" alt="Download the Shortcut" title="Download Notefy" />
      <img src="https://github.com/nicolodiamante/notefy/assets/48920263/1b89af88-b896-4029-b6c4-6a244db5ccfb" draggable="false" ondragstart="return false; "alt="Download the Shortcut" title="Download Notefy" width="600" />
    </picture>
  </a>
</p>

<br><br>

### Create your OpenAI API Key

To utilise ChatGPT's services with Siri, it is essential to obtain an OpenAI API key. To acquire this key, you need to generate a new secret key from your existing OpenAI account. If you don't have an OpenAI account yet, you can easily sign up for one by visiting the OpenAI signup page [here][openai-signup]. This secret key plays a crucial role in verifying your authentication. Here are the steps on how to do it:

1. Log in to your [OpenAI account][openai-account].
2. Search for the ‘Create new secret key’ option and click on it.

<p align="center">
  <picture>
    <img src="https://github.com/nicolodiamante/notefy/assets/48920263/70d2d961-c431-41ed-aa91-ecf9955ec590" draggable="false" ondragstart="return false; "alt="Create new secret key" title="Create new secret key" width="750px" />
  </picture>
</p>

Once you obtain the [API Key][openai-API], incorporating ChatGPT's services with Siri is straightforward. It's important to remember, that after making a copy of the key and closing the pop-up, you won't have access to it again. Therefore, store the key securely in a safe location.
<br><br>

<p align="center">
  <picture>
    <img src="https://github.com/nicolodiamante/notefy/assets/48920263/8d88b6f4-f46f-4b7b-b84e-bf76a95316f8" draggable="false" ondragstart="return false; "alt="OpenAI API Key" title="OpenAI API Key" width="750px" />
  </picture>
</p>

<br>

## Setting Up the Shortcut

After downloading the shortcut and copying your API key, follow these steps to put it to use:

- Begin by opening the Shortcuts app and finding the downloaded Notefy shortcut.

- Next, proceed with the configuration process. Carefully follow each step to tailor the shortcut according to your unique preferences. After completing these steps, the shortcut will be ready for immediate use.

> Note on API Key Storage Options: You have the flexibility to store your OpenAI API key in two ways. Firstly, you can directly embed it within the Notefy shortcut for convenience. Alternatively, for enhanced security, you may opt to use the Data Jar app to store the API key. If you decide on the latter, ensure that you have the Data Jar app installed. If not, or if you prefer a simpler approach, storing the API key directly in the shortcut remains a viable option.

<br>

<p align="center">
  <picture>
    <img src="https://github.com/nicolodiamante/notefy/assets/48920263/9fffbbfc-a42c-493e-8d1a-fc54efb386ac" draggable="false" ondragstart="return false;" alt="Paste your API keys" title="Paste your API keys" width="600px" />
  </picture>
</p>

<br>

Once the setup is complete, you're all set! The shortcut is designed to be straightforward and user-friendly.

<br><br>

## Using Notefy

Notefy offers multiple convenient activation methods:

- Activate with Siri: Begin by saying ‘Hey Siri’ followed by ‘Notefy’ to start the shortcut and it will begin listening straight away. Once you're done, tap the screen to indicate you've finished. The shortcut will then process the recorded audio and generate a concise summary.

<br>

<p align="center">
  <picture>
    <img src="https://github.com/nicolodiamante/notefy/assets/48920263/1733bca6-7f7b-4868-acf3-a3007fb47704" draggable="false" ondragstart="return false;" alt="Notefy Output" title="Notefy Output" width="1000px" />
  </picture>
</p>

<br>

- Summarise Text and Audio: Instantly understand the core of any text or audio content. Just send it to Notefy. The app promptly analyses and condenses the material into a brief, coherent summary. Whether it's a Safari text, a note, or a lengthy audio message from WhatsApp, Notefy seamlessly transforms any text or audio into a concise summary.

  Notes:

  - Click the Share icon (in the right top corner). &nbsp;&nbsp;<img src="https://github.com/nicolodiamante/notefy/assets/48920263/51acf6d7-bbc2-41cd-9d1e-592e2b2bbe68" draggable="false" ondragstart="return false;" alt="Share Icon" title="Share Icon" width="18px" />
  - Select ‘Send a Copy’. &nbsp;&nbsp;<img src="https://github.com/nicolodiamante/notefy/assets/48920263/2a9b536e-b193-496b-a810-76431aaba429" draggable="false" ondragstart="return false;" alt="Send a Copy Icon" title="Send a Copy Icon" width="14px" />
  - Scroll down and select Noefy. &nbsp;&nbsp;<img src="https://github.com/nicolodiamante/notefy/assets/48920263/81c16219-f639-477f-ba4f-5aeb5fd7cbdc" draggable="false" ondragstart="return false;" alt="Notefy Icon" title="Notefy Icon" width="16px" />

  Safari:

  - Click the Share icon (in the bottom). &nbsp;&nbsp;<img src="https://github.com/nicolodiamante/notefy/assets/48920263/2a9b536e-b193-496b-a810-76431aaba429" draggable="false" ondragstart="return false;" alt="Share Icon" title="Share Icon" width="14px" />
  - Scroll down and select Noefy. &nbsp;&nbsp;<img src="https://github.com/nicolodiamante/notefy/assets/48920263/81c16219-f639-477f-ba4f-5aeb5fd7cbdc" draggable="false" ondragstart="return false;" alt="Notefy Icon" title="Notefy Icon" width="16px" />

  Whatsapp:

  - Hover over the audio message you wish to summarise.
  - Click ‘Forward’ in the appearing menu. &nbsp;&nbsp;<img src="https://github.com/nicolodiamante/notefy/assets/48920263/d04cc23e-2101-4f66-96ed-92178bd9b8ff" draggable="false" ondragstart="return false;" alt="Forward Icon" title="Forward Icon" width="19px" />
  - Choose the individual chat you want to summarise. &nbsp;&nbsp;<img src="https://github.com/nicolodiamante/notefy/assets/48920263/d1344e90-d823-4f85-a192-f3818be3b1aa" draggable="false" ondragstart="return false;" alt="Done Icon" title="Done Icon" width="18px" />
  - Click the Share icon (in the right bottom corner). &nbsp;&nbsp;<img src="https://github.com/nicolodiamante/notefy/assets/48920263/2a9b536e-b193-496b-a810-76431aaba429" draggable="false" ondragstart="return false;" alt="Share Icon" title="Share Icon" width="14px" />
  - Select Notefy. &nbsp;&nbsp;<img src="https://github.com/nicolodiamante/notefy/assets/48920263/81c16219-f639-477f-ba4f-5aeb5fd7cbdc" draggable="false" ondragstart="return false;" alt="Notefy Icon" title="Notefy Icon" width="16px" />

- Mac Integration: Notefy integrates smoothly with the Mac workflow. Whether the text is in Notes or online, just highlight it and access Notefy via the Services menu with a right-click. This allows for the rapid conversion of lengthy texts into summaries.

<br><br><br>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github.com/nicolodiamante/notefy/assets/48920263/5e54f6f2-a192-47cf-a6a7-b996f05c00ac" draggable="false" ondragstart="return false;" alt="Quick Actions Menu" title="Quick Actions Menu" />
    <img src="https://github.com/nicolodiamante/notefy/assets/48920263/1693af1a-b2c9-4a91-889b-c3286dcb6112" draggable="false" ondragstart="return false; "alt="Quick Actions Menu" title="Quick Actions Menu" width="600px" />
  </picture>
</p>

<br><br><br>

Notefy streamlines summarising, transforming it into a straightforward and enjoyable activity. Crafted as a shortcut for efficiency, it guarantees reliability and simplicity in use. Ideal for busy schedules or focused work sessions.

<br><br>

## Notefy Privacy

As a shortcut within the Apple ecosystem, Notefy already benefits from inherent protection, even when interacting with third-party service providers. However, it relies on the OpenAI API for its full functionality. If you are hesitant about sharing information with third-party services, Notefy may not be suitable for you. For those considering using Notefy, it's recommended to first review the Privacy Policies of [OpenAI][openai-privacy] to help you make a well-informed decision.

<br><br>

<p align="center">
  <picture>
    <img src="https://github.com/nicolodiamante/notefy/assets/48920263/234cd4f6-c82c-445e-a22b-46bb53a71687" draggable="false" ondragstart="return false;" alt="Shortcut Privacy" title="Shortcut Privacy" width="900px" />
  </picture>
</p>

<br><br>

## Notes

### Resources

#### Apple

- [Apple Siri][apple-siri]
- [Apple Shortcuts User Guide][apple-shortcuts-guide]

#### OpenAI

- [OpenAI Documentation][intro]
- [OpenAI Examples][examples]
- [OpenAI Playground][playground]
- [OpenAI Models][openai-models]
- [OpenAI Chat Completions][chat-completions]
- [OpenAI Whisper][whisper]

#### Data Jar

- [Data Jar][data-jar]

### Contribution

Thank you for your interest in this shortcut. Your feedback would be much appreciated. If you encounter any issues or bugs, please feel free to report them on the [issues page][issues].

<br><br>

<p align="center">
  <picture>
    <img src="https://github.com/nicolodiamante/notefy/assets/48920263/bed7bb0e-88a4-4e2e-915c-ab03a7360cef" draggable="false" ondragstart="return false;" /></>
  </picture>
</p>

<p align="center">
  <a href="https://nicolodiamante.com" target="_blank">
    <img src="https://github.com/nicolodiamante/notefy/assets/48920263/99d09812-d66b-46f6-9cf3-10b1805bd164" draggable="false" ondragstart="return false;" alt="Nicol&#242; Diamante Portfolio" title="Nicol&#242; Diamante" width="17px" />
  </a>
</p>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github.com/nicolodiamante/notefy/assets/48920263/0fda6dc3-8922-44f1-a29c-7333aaf395ec" draggable="false" ondragstart="return false;" alt="MIT License" title="MIT License" />
    <img src="https://github.com/nicolodiamante/notefy/assets/48920263/01026a71-3775-4925-b814-1f6ae5332512" draggable="false" ondragstart="return false; "alt="MIT License" title="MIT License" width="95px" />
  </picture>
</p>

<!-- Link labels: -->

[openai-account]: https://auth0.openai.com/u/login/identifier?state=hKFo2SBWNUdMbnRYYTFTeFdkNW1rUEY5cHNyUVMxdE9FdjdxYqFur3VuaXZlcnNhbC1sb2dpbqN0aWTZIDJVOVBFOWdJZkw4WEdpbmsxQ1JRRTEydWY5LXlzYUxFo2NpZNkgRFJpdnNubTJNdTQyVDNLT3BxZHR3QjNOWXZpSFl6d0Q
[openai-signup]: https://auth0.openai.com/u/signup/identifier?state=hKFo2SBjY3ExRFozSEdJRVhCQ0hnYkRETjRzM3p3TlV4bjl6a6Fur3VuaXZlcnNhbC1sb2dpbqN0aWTZIFNPWE1oRVdWMm1ZZjU2Rm5UVHcybF9ya3JlU1hCaGd5o2NpZNkgRFJpdnNubTJNdTQyVDNLT3BxZHR3QjNOWXZpSFl6d0Q
[openai-API]: https://beta.openai.com/account/api-keys
[openai-models]: https://platform.openai.com/docs/models
[apple-shortcuts-guide]: https://support.apple.com/en-gb/guide/shortcuts/apd58d46713f/ios
[apple-shortcuts-download]: https://apps.apple.com/us/app/shortcuts/id915249334
[notefy-shortcut]: https://www.icloud.com/shortcuts/499c51a5d676459e87510fd7cf45e731
[openai-privacy]: https://openai.com/policies/privacy-policy
[apple-siri]: https://www.apple.com/siri/
[chaGPT]: https://openai.com/blog/chatgpt
[whisper]: https://openai.com/research/whisper
[playground]: https://platform.openai.com/playground
[examples]: https://platform.openai.com/examples
[intro]: https://platform.openai.com/docs/introduction
[chat-completions]: https://platform.openai.com/docs/guides/chat
[data-jar]: https://datajar.app
[issues]: https://github.com/nicolodiamante/notefy/issues