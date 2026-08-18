# Meme@Me Weekly Review Cadence (MeMeMe-LLP)

## Schedule & Allocation
- **Timing**: Every Tuesday, 3:00 PM – 6:00 PM EST (3-hour focused operating block).
- **Participants**: Product Lead, Game Engineer, Brand/Artist Coordinator.

---

## Standard 3-Hour Review Agenda

### Hour 1: Business, Financials & Steam Metrics (3:00 PM – 4:00 PM)
1. **Steam Wishlist & Conversion Tracking**:
   - Weekly delta in wishlist volume, regional velocity (US, JP, KR, EU).
   - Traffic source attribution (TikTok, YouTube Shorts, Twitch referral).
2. **Twitch Partner & Bit Revenue Performance**:
   - Top 10 streamer Bit earnings generated via Meme@Me proxy.
   - Streamer retention & multi-session activation rates.
3. **Budget & Financial Review**:
   - Contractor/artist payments, server & domain operating costs.

---

### Hour 2: Creative & Artist Synchronization (4:00 PM – 5:00 PM)
1. **Looney-Tunes Asset Pipeline Review**:
   - Review newly delivered meme sprites, 2D animations (anvils, wrecking balls, paint splatters).
   - Audio sound effect mixing (crunchy cartoon impact SFX, doge barking, custom Bit jingles).
2. **Influencer Campaign Outreach Check**:
   - Key claim rate from the 50-streamer target roster.
   - Moderation feedback from live stream trials.

---

### Hour 3: Game Engine & Technical Integration (5:00 PM – 6:00 PM)
1. **Physics Engine & Overlay Stress Test**:
   - 50-item concurrent meme spawn stability and frame pacing (>60 FPS on 1080p/1440p).
   - Screen collision bounds across multi-monitor streamer configurations.
2. **Twitch EventSub & Proxy Reliability**:
   - Webhook delivery latency (<200ms from Bit cheer to screen spawn).
   - Steamworks build deployment checks via SteamPipe.

---

## Operating Checklist (Run Before Every Release)
- [ ] Vercel landing page (`www.memememememe.me`) health verified.
- [ ] Local Twitch proxy daemon unit tests passing (`npm test` in `meme-me-cli`).
- [ ] Godot desktop engine exports clean build for Windows (`.exe`) and macOS (`.dmg`).
- [ ] Steam achievements test suite passing in sandbox mode (`SteamAppId=480`).
