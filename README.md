<p align="center">
  <a href="https://github.com/euandresimoes/verus">
      <img src="https://img.shields.io/badge/🚀-REPO-FFE162?style=for-the-badge&labelColor=000000"/>
  </a>
  &nbsp;&nbsp;
  <a href="https://www.npmjs.com/package/verus-cli">
    <img src="https://img.shields.io/npm/v/verus-cli?label=%F0%9F%93%A6+NPM&labelColor=black&color=%233F0071&style=for-the-badge"/>
  </a>
  &nbsp;&nbsp;
  <img src="https://img.shields.io/github/stars/euandresimoes/verus?style=for-the-badge&label=%E2%AD%90%20STARS&labelColor=black&color=%23FB2576"/>
  &nbsp;&nbsp;
  <img src="https://img.shields.io/github/repo-size/euandresimoes/verus?style=for-the-badge&label=%F0%9F%9B%A0%EF%B8%8F%20SIZE&labelColor=black&color=%23332FD0"/>
</p>

![Verus Banner](https://github.com/user-attachments/assets/5173589a-5dd8-4fd4-9536-7e039365acae)

# 📦 Verus CLI - The AI-Powered Commit Assistant

[🇺🇸 EN](https://github.com/euandresimoes/verus/blob/master/README.md) | [🇪🇸 ES](https://github.com/euandresimoes/verus/blob/master/README.es.md) | [🇧🇷 PT-BR](https://github.com/euandresimoes/verus/blob/master/README.pt-br.md) 

**Verus** is a command-line tool (CLI) that integrates AI to automatically generate commit messages for your Git repositories. From a brief description of the changes made to the files, Verus uses OpenAI's API to suggest a formatted commit message, such as:

`✨ feat(auth/signup): implemented email verification`

---

## 📋 Requirements

To use **Verus**, you need an **OpenAI API Key** with at least **$0.50 of credit**.

---

## 💻 Installation

To install **Verus CLI** globally, run the following command in your terminal:

```bash
npm install -g verus-cli
```

---

## 🚀 How to Use

1. **Add Your API Key**  
   To configure your **OpenAI API Key**, use the following command:

   ```bash
   verus -k <apikey>
   ```

   Replace `<apikey>` with your personal OpenAI API key.

2. **Start Verus CLI**  
   To run Verus, simply type the following command:

   ```bash
   verus
   ```

---

## ▶️ Usage Flow

1. **File Selection:** Verus will list the modified files, and you will select which ones you want to include in the commit.  
2. **Describe Your Changes:** After selecting the files, you will provide a brief summary of the changes made.  
3. **Commit Message Generation:** OpenAI's AI processes the summary and suggests a formatted commit message, such as:

   ```bash
   🧪 test(utils/date): added unit tests for formatDate function
   ```

5. **Commit Ready:** Once confirmed, Verus automatically creates the commit with the generated message.

---

## 📝 License

This project is licensed under the MIT License.  
Feel free to use, modify, and distribute it as you wish — just give proper credit. 🤝

See the full license in the [LICENSE](./LICENSE) file.

---

## 🤝 Contributions

Feel free to open a pull request or report any issues if you’d like to contribute to the development of Verus. 🚀
