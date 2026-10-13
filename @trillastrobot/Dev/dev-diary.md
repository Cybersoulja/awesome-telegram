# 📓 Development Diary: Trill Astro Telegram Mini App

## 🚀 CURRENT STATE
- **Active Module:** Telegram Mini App Backend & Authentication Bridge
- **Status:** Initializing project structure and HMAC security verification layer.
- **Milestone:** Baseline setup completed; ready for route integration.

---

## 🎯 NOW (Active Milestone)
- [ ] **Secure Authentication:** Implement HMAC-SHA256 signature verification for incoming Telegram `initData`.
- [ ] **Environment Security:** Ensure bot tokens are loaded strictly via environment variables (never hardcoded).

## 🔭 NEXT (Upcoming Milestone)
- [ ] **API Endpoint Integration:** Wrap the validation script into a lightweight web framework (e.g., FastAPI or Flask).
- [ ] **Frontend SDK Bridge:** Initialize `@twa-dev/sdk` in the frontend layer to pass cryptographically signed `initData` to our backend.

## 🔮 LATER (Future Scope)
- [ ] **Web3 / TON Integration:** Add TON Connect wallet authorization for user state management.
- [ ] **Hugging Face Model Inference:** Connect user requests inside the Mini App to an optimized open-weight HF Space backend.

---

## ✅ VERIFICATION LOG
- **Local Runtime Check:** Run syntax and unit validation via WebContainer terminal.
- **Success Criteria:** Validation script successfully flags tampered `initData` payloads and authenticates valid tokens.