# 遥感解译平台
## 前端：Vue 3 + TypeScript + Vite
## 后端：python
## 数据集：LEVIR-CD

### 基本完成前后端交互搭建
![image](https://github.com/user-attachments/assets/97f23531-0307-4a81-8d49-afbfe560d4f6)


## 帮助文档：
This template should help get you started developing with Vue 3 and TypeScript in Vite. The template uses Vue 3 `<script setup>` SFCs, check out the [script setup docs](https://v3.vuejs.org/api/sfc-script-setup.html#sfc-script-setup) to learn more.

Learn more about the recommended Project Setup and IDE Support in the [Vue Docs TypeScript Guide](https://vuejs.org/guide/typescript/overview.html#project-setup).

在本研究中，我们采用了Vue.js作为前端框架，结合Element Plus UI组件库和Remix Icon图标库，构建了一个高效、响应式的用户界面。Vue.js的组件化开发模式和渐进式框架特性，使得前端开发更加模块化和高效。Element Plus提供了丰富的UI组件，加快了界面开发速度，而Remix Icon则提供了高质量的SVG图标，支持多种格式，便于设计美观的用户界面。前端通过Axios与后端进行数据交互，Axios支持Promise，简化了异步操作，提高了通信效率。

后端方面，我们选择了Python及其Flask框架来构建API。Python简洁的语法和强大的标准库为快速开发提供了基础，而Flask的轻量级和灵活性使其成为处理前后端交互的理想选择。Flask-Cors用于解决跨域问题，确保前后端之间的正常通信。PyMySQL作为MySQL的Python客户端库，支持事务和存储过程，确保了数据操作的稳定性和安全性。

通过上述技术的结合，我们实现了前后端的高效协作。Vue.js和Flask的组合不仅提高了开发效率，还确保了应用的性能和可扩展性。这些技术的选择为LSTM预测模型的实现提供了坚实的技术基础，同时保证了项目的快速迭代和部署能力。

### 前端技术要点

1. **Vue.js**：作为前端的核心框架，Vue.js以其渐进式的设计理念，允许开发者逐步引入其功能，从而降低了开发门槛。其组件化开发模式提高了代码的复用性和可维护性，使得前端界面的构建更加模块化和高效。

2. **Element Plus**：作为Vue 3的官方UI组件库，Element Plus提供了丰富的组件和美观的界面设计，极大地加快了前端界面的开发速度。其与Vue 3的深度集成确保了组件的高性能和易用性。

3. **Remix Icon**：作为图标库，Remix Icon提供了高质量的SVG图标，支持多种格式，便于设计美观且响应式的用户界面。其开源特性也保证了使用的灵活性和成本效益。

4. **Axios**：用于前后端数据交互的HTTP客户端库，Axios支持Promise，简化了异步操作，使得前后端通信更加简洁和高效。

5. **Pinia**：作为Vue.js的状态管理库，Pinia提供了简洁的API和TypeScript支持，是Vuex的轻量级替代品。它允许跨组件或页面共享状态，提高了应用的状态管理效率。

### 后端技术要点

1. **Python**：作为后端开发语言，Python以其简洁的语法和强大的标准库，为快速开发提供了坚实的基础。其在数据科学和机器学习领域的广泛应用，也使得Python成为实现LSTM预测模型的首选语言。

2. **Flask**：作为后端框架，Flask以其轻量级和灵活性，适合快速构建API。其简单的配置和扩展性，使得Flask成为处理前后端交互的理想选择。

3. **Flask-Cors**：用于解决前后端跨域问题，确保了前后端之间的正常通信。其简洁的配置方式，使得跨域处理变得简单高效。

4. **PyMySQL**：作为MySQL的Python客户端库，PyMySQL支持事务和存储过程，便于与MySQL数据库进行交互，确保了数据操作的稳定性和安全性。

### 前后端连接方法

1. **API设计**：在后端使用Flask定义RESTful API接口，确保前后端之间的数据交互遵循统一的接口规范。

2. **数据交互**：前端通过Axios发送HTTP请求到后端API，后端接收数据并进行处理，返回响应结果。这种基于HTTP的通信方式，保证了前后端的解耦和独立性。

3. **跨域处理**：通过Flask-Cors解决前后端跨域问题，确保请求能够正常发送和接收，从而实现高效的数据交互。

### 技术选择的优势

- **Vue.js**：其组件化开发模式和渐进式框架特性，使得前端开发更加高效和模块化。
- **Element Plus**：丰富的UI组件和美观的界面设计，加快了前端界面的开发速度。
- **Remix Icon**：高质量的SVG图标支持，便于设计美观的用户界面。
- **Axios**：简化异步操作，提高前后端通信效率。
- **Pinia**：简洁的API和TypeScript支持，提高状态管理效率。
- **Python**：简洁语法和强大的标准库，适合快速开发和实现复杂算法。
- **Flask**：轻量级和灵活性，适合构建API和处理前后端交互。
- **Flask-Cors**：简洁配置，有效解决跨域问题。
- **PyMySQL**：支持事务和存储过程，确保数据操作的稳定性和安全性。
