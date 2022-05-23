```typescript
class Profile {
    get name(): string {
        return "Matheus Chimelli"
    }

    get skills():string[] {
        return ["Node.js", "Javascript", "Typescript", "Postgres", "ElasticSearch", "MongoDB", "React", "NextJS","Firebase"]
    }

    get bio():string {
        return ``
    }

    get hireable():boolean {
        const bioText = this.bio
        const isHireable = bioText.match(/looking for a job/)
        if (isHireable && isHireable[0]) return true
        return false
    }
}

```

<!--
**matheuschimelli/matheuschimelli** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
