
Solve the problem that app cannot detect mipush on not xiaomi device, use it with <a href="https://github.com/MiPushFramework/MiPushFramework">MiPushFramework</a>

伪装机型让普通应用能够正确识别到MiPush，搭配<a href="https://github.com/MiPushFramework/MiPushFramework">MiPushFramework</a>使用。

伪装逻辑来源于<a href="https://github.com/MiPushFramework/MiPushEnhancement">MiPushEnhancement</a>，代码上比MiPushEnhancement更简单一些，但是改了检测和应用规则，只要检测到mipush sdk就会生效，理论上bug会少一点，适合lsposed和edxposed白名单使用，勾选自己需要伪装的应用即可，当然全局使用应该也是没什么问题的。