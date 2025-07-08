## 📊 YouTube Subscriber Counter Instructions

To use the subscriber counter, you’ll need to **invite** `API@Seed.soy` as a **Viewer** on the YouTube channel you want to monitor.  
> ⚠️ **Note:** Invitations must be accepted manually, so it may take a few hours before your channel is usable.

This process is necessary because the official YouTube API no longer returns your real subscriber count.

- **How to invite a Viewer:**  
  See [YouTube Studio Permissions Guide](https://support.google.com/youtube/answer/9481328)

---

### 🔗 API Endpoint

If you want to build your own counter, you can use this API endpoint to get a channel’s subscriber count:

```
https://api.seed.soy/get_creator_counts/creator_subscriber_count?channel=CHANNEL_ID
```

Replace `CHANNEL_ID` with your channel’s ID.

---

### 🌐 Web Tool

You can also use the web tool directly:

- Replace `YOUR_CHANNEL_ID` with your channel’s ID.
- Replace `DIGITS_IN_YOUR_SUBSCRIBER_COUNT` with the number of digits you want to display (e.g., `3` for 123, `4` for 1,234).

---
