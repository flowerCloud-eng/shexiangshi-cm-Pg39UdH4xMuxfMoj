
　　在 Build 2024 上，WinUI 团队宣布将重新关注 WinUI，将其作为我们推荐的原生 Windows 应用开发的首要应用开发框架之一。为了使其尽可能无缝和轻松地进入编码，我们创建了一个新的 Windows Dev Center 页面，简化了我们的 Getting Started with WinUI 文档，并与 Visual Studio 合作来改善开发人员在工作负荷和模板方面的体验。今天，我们将专注于向您展示 Visual Studio 中伟大的新变化，以及我们背后的一些思考过程和链接，以了解更多!


![](https://img2024.cnblogs.com/blog/270073/202407/270073-20240725093353744-1660934958.png)


# **开始使用新的工作负荷**


　　在 Visual Studio 17\.10 中，新的“Windows application development”工作负荷现在可供开发人员使用，只需单击一下，就可以使用 .NET 或 C\+\+ 编写时尚，现代和快速的 WinUI 应用程序。这个工作负荷取代了旧的“Universal Windows Platform development”工作负载，使用针对最新一代 WinUI \+ Windows App SDK 的工具。WinUI 模板也在 New Project 模板列表中被赋予了一个新的图标和优先级提升，它们现在包括一个新的社区请求的 Unit Test 模板，以帮助更轻松地测试 WinUI 应用程序!


　　要开始使用新的工作负荷，请遵循以下简单步骤:


　　1\. 打开 Visual Studio 安装程序。


　　2\. 在 Workloads \> Desktop \& Mobile 下，选择“Windows application development”工作负荷。


　　如果您正在用 C\# 开发，恭喜您，您完成了！工作负荷默认包括 .NET WinUI app 开发工具。


　　3\. 如果您想用 C\+\+ 开发或者如果您需要 Universal Windows Development 工具，选择可选的“C\+\+ WinUI app development tools”组件。这将自动选择 Universal Windows Platform 工具和 C\+\+ Universal Windows Platform 工具组件。


![](https://img2024.cnblogs.com/blog/270073/202407/270073-20240725093425706-2037482585.png)


　　就是这样！在以前的 Visual Studio 版本中，要使用 WinUI \+ Windows App SDK 进行开发，您必须在可选组件列表中手动搜索每个必需的组件——这是在阅读文档以找出您需要的组件之后!我们还听到反馈说，Windows App SDK 中的 WinUI，代表了继承 Universal Windows Platform(UWP) 的最新一代 WinUI，不如它的前身那么突出。有了新的工作负荷和组件，我们已经解决了这些反馈，使最新的工具和 API 变得清晰，处于中心位置，一键即可使用！


# **充分利用 WinUI 模板的改进**


　　一旦安装了“Windows application development”工作负荷，现在就可以开始创建项目了。我们在新项目界面上也得到了一些很好的反馈——WinUI 模板排在列表的后面，这使得它们看起来没有其他模板那么重要，它们需要重新涂装。我们听到了您的声音，所以我们把最常用的 WinUI 模板放在了更靠前的位置，并添加了一个闪闪发光的新图标!


　　Go to File \> New Project 看看这些更新！


![](https://img2024.cnblogs.com/blog/270073/202407/270073-20240725093503801-764251175.png)


　　其余的模板也不太靠下；在大多数显示器上，您可能不需要滚动屏幕就能看到它们。在这个列表中还有一个我们想要强调的东西——WinUI 的新 Unit Test 模板！这是你们，WinUI 开发者社区一直想要的，我们很高兴将它与我们对 WinUI 负荷和模板体验的其他改进一起推出。


# **小结**


　　我们想再次感谢您为我们所做的一切。你们帮助新的 WinUI 开发者更容易接受 Windows 上的原生应用开发，并帮助我们在 Windows 上创造出最好的原生应用开发体验。


　　要直接在平台上给我们反馈，请访问我们的 GitHub，或在 Twitter 上关注我们以了解最新的发布和新闻。


　　要了解更多关于 WinUI 的信息和更多关于入门的信息，请查看我们新的 Windows 开发中心页面 https://aka.ms/windev。


　　如果您对我们在 Build 2024 上讨论的内容的全貌感兴趣，除了我们的 Visual Studio 更新，看看以下内容:


　　\- Navigating Win32 App Development with WinUI and WPF \| BRK241 (youtube.com)


　　\- How to create superior experiences with WinUI and WPF \| BRK244 (youtube.com)


　　我们感谢您花时间报告问题/建议，并希望您在使用 Visual Studio 时继续给我们反馈，告诉我们您喜欢什么以及我们可以改进什么。您的反馈对于帮助我们使 Visual Studio 成为最好的工具至关重要！您可以通过开发者社区与我们分享反馈，通过发送反馈来报告问题或分享您的建议，推动对新功能或现有功能的改进。


　　通过在 YouTube, Twitter, LinkedIn, Twitch 和 Microsoft Learn 上关注我们与 Visual Studio 团队保持联系。


 


原文链接：https://devblogs.microsoft.com/visualstudio/dive\-into\-native\-windows\-development\-with\-new\-winui\-workload\-and\-template\-improvements/


![](https://img2024.cnblogs.com/blog/270073/202407/270073-20240725093550267-983086319.webp)


 


 本博客参考[悠兔机场](https://xinnongbo.com)。转载请注明出处！
