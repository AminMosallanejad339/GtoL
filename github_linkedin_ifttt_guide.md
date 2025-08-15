# How to Connect GitHub to LinkedIn Using IFTTT

This guide shows how to automatically share your GitHub repositories on your LinkedIn profile using **IFTTT**.

---

## 1. Sign Up / Log In to IFTTT

1. Go to [IFTTT](https://ifttt.com/explore).
2. Log in with your account or create a new one.

---

## 2. Create a New Applet

1. Click **Create**.
2. Click **If This** to choose the trigger.

---

## 3. Set GitHub as the Trigger

1. Search for **GitHub** and select it.
2. Choose the trigger:
   - **New repository by a specific username or organization**
     > This triggers every time a new repository is created by the specified GitHub username.
3. Connect your GitHub account (e.g., `AminMosallanejad339`).
4. Enter your GitHub username in the field.

---

## 4. Set LinkedIn as the Action

1. Click **Then That** to choose the action.
2. Search for **LinkedIn** and select it.
3. Choose **Share a link** as the action.
4. Connect your LinkedIn account (e.g., `Amin Mosallanejad`).

---

## 5. Customize the LinkedIn Post

1. In the **What would you like to share about the link?** field, use:

```markdown
🚀 New GitHub Repository Alert! 🚀

{{RepositoryName}} by {{OwnerUsername}}

{{RepositoryDescription}}

🔗 Explore it here: {{RepositoryURL}}
```

2. For **Link URL**, use:

```markdown
{{RepositoryURL}}
```

3. Optionally, you can add additional ingredients like `CloneURL` or `CreatedAt`.

---

## 6. Review and Finish

1. Click **Continue**.
2. Review your Applet:

```markdown
If New repository by AminMosallanejad339, then share a link on your profile
```

3. Click **Finish** to activate the Applet.

---

## 7. Important Notes

- **New repositories only:** IFTTT will post only repositories created **after the Applet is activated**.
- **Repository field:** You cannot leave the repository field blank; use your GitHub username.
- **LinkedIn post limit:** Each post is limited to **3000 characters**.
- **Dynamic fields:** Ingredients like `{{RepositoryName}}`, `{{OwnerUsername}}`, and `{{RepositoryURL}}` are automatically replaced by GitHub data.

---

## 8. Visual Flow

GitHub → IFTTT Applet → LinkedIn

- **Trigger:** New repository by your GitHub username
- **Action:** Share a link on LinkedIn

---

 

![image-20250815125712562](C:\Users\mosal\AppData\Roaming\Typora\typora-user-images\image-20250815125712562.png)

