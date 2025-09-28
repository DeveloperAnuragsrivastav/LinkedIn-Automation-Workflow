

````markdown
# LinkedIn Automation Workflow 🚀

**Automate your LinkedIn posting – at zero cost!**

This project is a **zero-cost LinkedIn automation system** that streamlines content creation, approval, and posting. It leverages AI to generate posts, suggest images, and schedule content efficiently—all in a single click.


---

## preview 👁️

<img width="1366" height="764" alt="screencapture-linkedin-feed-update-urn-li-activity-7378084249456803840-2025-09-28-20_43_43" src="https://github.com/user-attachments/assets/12930f3a-41ee-4a62-b632-9777b4ddba4e" />


---

## Features ✨

- **AI-Powered Content Generation:** Automatically creates original and engaging LinkedIn posts.
- **One-Click Approval:** Approve or reject posts instantly via Telegram buttons.
- **AI Image Suggestions:** Recommends relevant visuals without additional cost.
- **Smart Scheduling:** Posts go live at optimal times for engagement.
- **Zero Cost:** No subscription fees or hidden charges.

---

## How It Works ⚡

1. **Content Generation:** AI generates LinkedIn posts based on your inputs.
2. **Approval Process:** Posts are sent to Telegram where you can approve or reject them instantly.
3. **Image Suggestions:** AI recommends images to accompany your posts.
4. **Smart Scheduling:** Approved posts are automatically scheduled to publish at the best times.

---

## Benefits ✅

- Saves hours of manual effort each week
- Maintains consistent and professional LinkedIn presence
- Lets you focus on creating value, not managing posts

---

##  Workflow Overview ⚡


1. **Cron Trigger Node** – Runs the workflow on a schedule.  
2. **AI Content Generation Node (HTTP Request / AI Node)** – Generates LinkedIn posts from your input prompts.  
3. **Telegram Node** – Sends posts to Telegram for one-click approval.  
4. **Decision Node** – Checks Telegram responses: Approve → Continue, Reject → Stop.  
5. **AI Image Suggestion Node (Optional)** – Generates suggested images for posts.  
6. **LinkedIn Posting Node (HTTP Request)** – Publishes approved posts to LinkedIn.  
7. **Notification Node (Optional)** – Sends logs or summaries to Telegram or Slack.

---

## Contributing 🤝

Contributions are welcome! Feel free to open issues or submit pull requests.

---

## License 📄

This project is licensed under the MIT License.

```


