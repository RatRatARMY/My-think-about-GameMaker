## GameMaker is Unsafe for Commercial Projects (For Now)

Why do I say that?

1. **Extremely high fee for source code access**  
   - $799.99/year or $79.99/month  
   - Yet access is *limited, revocable, non-sublicensable, and non-transferable*  
   - 📌 Refer to **Section 2** of the *GameMaker Source Code License Agreement*

2. **You don’t truly “own” the runtime**  
   - You cannot use, publish, fork, or embed the runtime in any way beyond temporary debugging  
   - No redistribution or custom tooling is allowed

3. **No forking or multi-project flexibility**  
   - The license is restricted to a *single product scope*  
   - You are not allowed to use modified code across multiple projects  
   - 📌 Refer to **Section 2** again – only "your Product" is permitted

4. **No compatibility with GPL/LGPL or most open-source libraries**  
   - GPL/LGPL are **explicitly prohibited**  
   - Only dynamic linking is allowed, and even that carries legal risk  
   - 📌 Refer to **Section 3** of the License Agreement

5. **No CI/CD or automated build support**  
   - Any automation or distribution of runtime builds violates the license  
   - This makes GameMaker unsuitable for modern development pipelines or studio-scale deployment

---

### ❌ Conclusion

> **You pay like it’s yours — but you can’t use it like it’s yours.**

GameMaker today is built around control and restriction — not collaboration or scalability.

If you’re looking for a tool for quick prototyping, GameMaker might work for you.  
But if you’re serious about building and selling games — **this is not an engine you can trust long-term.**

---

### 🔁 Alternatives

1. **Godot Engine** – Fully open source (MIT license)  
2. **Unreal Engine** – Semi-open with a fair commercial model  
3. **Custom C++ Engines** using **SDL**, **SFML**, or **OpenGL/Vulkan** with open licensing

---

### 📄 License Source

The official GameMaker Source Code License Agreement (subject to change):  
🔗 [https://gamemaker.io/en/legal/sourcecode](https://gamemaker.io/en/legal/sourcecode)
