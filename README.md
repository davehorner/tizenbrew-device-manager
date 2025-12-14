# 🍺 TizenBrew Device Manager

<p align="center">
    <img width="700px" src="./.github/assets/TizenBrew_Official_Banner.png">
    <br>
    <sub> TizenBrew logo, banner and README by <a href="https://github.com/Zyborg777">@Zyborg777</a> </sub>
</p>

### Manage your Tizen device, without Tizen Studio.

<p align="center">
    <a href="https://discord.gg/m2P7v8Y2qR">
        <picture>
            <source height="24px" media="(prefers-color-scheme: dark)"
                srcset="https://user-images.githubusercontent.com/13122796/178032563-d4e084b7-244e-4358-af50-26bde6dd4996.png" />
            <img height="24px"
                src="https://user-images.githubusercontent.com/13122796/178032563-d4e084b7-244e-4358-af50-26bde6dd4996.png" />
        </picture>
    </a>&nbsp;&nbsp;&nbsp;
    <a href="https://reddit.com/r/TizenTube">
        <picture>
            <source height="24px" media="(prefers-color-scheme: dark)"
                srcset="https://user-images.githubusercontent.com/13122796/178032351-9d9d5619-8ef7-470a-9eec-2744ece54553.png" />
            <img height="24px"
                src="https://user-images.githubusercontent.com/13122796/178032351-9d9d5619-8ef7-470a-9eec-2744ece54553.png" />
        </picture>
    </a>&nbsp;&nbsp;&nbsp;
    <a href="https://www.youtube.com/@tizenbrew">
        <picture>
            <source height="24px" media="(prefers-color-scheme: dark)"
                srcset="https://user-images.githubusercontent.com/13122796/178032714-c51c7492-0666-44ac-99c2-f003a695ab50.png" />
            <img height="24px"
                src="https://user-images.githubusercontent.com/13122796/178032714-c51c7492-0666-44ac-99c2-f003a695ab50.png" />
        </picture>
    </a>
</p>

## Installation

To install and use the TizenBrew Device Manager, follow these steps:

### Prerequisites

Ensure you have the following installed on your system:
- [Node.js](https://nodejs.org/) (v16 or later recommended)
- [Rust](https://www.rust-lang.org/) (latest stable version)
- [Tauri prerequisites](https://tauri.app/v1/guides/getting-started/prerequisites) for your operating system

### Steps

1. Clone the repository:
   ```bash
   git clone https://github.com/reisxd/tizenbrew-device-manager.git
   cd tizenbrew-device-manager
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Build the project:
   ```bash
   npm run build
   ```

4. Run the application:
   ```bash
   npm run tauri dev
   ```

5. To create a production build:
   ```bash
   npm run tauri build
   ```

---