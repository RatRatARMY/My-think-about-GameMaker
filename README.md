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
   - License is restricted *per product*  
   - You are not allowed to use modified code across multiple projects  
   - 📌 Refer to **Section 2**, again – only "your Product" is permitted

4. **No compatibility with GPL/LGPL or most open-source libraries**  
   - GPL/LGPL are **explicitly prohibited**  
   - Only dynamic linking is tolerated, and even that is legally risky  
   - 📌 Refer to **Section 3** of the License Agreement

5. **No CI/CD or automated build support**  
   - Any automation or sharing of runtime build violates the license  
   - This makes GameMaker unsuitable for professional pipelines or studios

---

### ❌ Conclusion
> **You pay like it’s yours — but you can’t use it like it’s yours.**

GameMaker today is structured around control and restriction — not collaboration or scalability.

If you find a game engine that can use for prototype project, GameMaker is for you.

If you’re serious about making and selling games — this isn’t the engine to trust for the long haul.

---

### Alternative

1. Godot Engine (MIT-licensed)
2. Unreal Engine (semi-open but with fair commericial model)
3. Custom engines use SDL/SFML with open licenses
