# Polymarket Quantitative Analysis - 2026-02-05

## 📊 Monitor Execution Summary
- **Billboard Monitor**: ✅ Success
- **Netflix Monitor**: ⚠️ Partial (Fixed during session)
- **Data Timestamp**: 2026-02-05 04:15 UTC

---

## 🎵 Billboard Hot 100 Analysis
**Market**: *Billboard Hot 100 #1 Song Week of February 7*
- **Monitor Data**: #1 Song is **"Aperture" by Harry Styles**.
- **Polymarket Status**: Market already proposed/resolved as **YES**.
- **Discrepancy**: None. The market followed the data perfectly.

---

## 🎬 Netflix US Movie Top 10 Analysis
**Market**: *What will be the top US Netflix movie this week (February 10)?*
- **Candidates & Pricing**:
  1. **The Investigation of Lucy Letby**: 76¢ (67% Mid)
  2. **Copshop**: 36¢ (25% Mid)
  3. **The Rip**: 5.7¢ (5% Mid)
- **Real-World Data (Feb 4, 2026)**:
  - **#1 Daily (US)**: `Copshop` (Holding for 3 days)
  - **#7 Daily (US)**: `The Rip` (Fading after 19 days)
  - **Unranked**: `The Investigation of Lucy Letby` (Released Feb 4, not yet in Top 10)
- **Analysis**: 
  - There is a significant discrepancy between current daily performance and market pricing. `Copshop` is the actual #1 but is priced at roughly half the probability of `Lucy Letby`.
  - `The Investigation of Lucy Letby` is a high-profile true crime documentary released yesterday. The market is pricing in a massive surge that hasn't materialized in the Top 10 yet.
  - **Alpha**: `Copshop` at 36¢ offers high value if the documentry fails to dominate the weekend.

---

## 🛠 Maintenance & Sync
- Fixed `monitoring/polymarket/netflix_monitor.py` logic to handle newer page structures.
- Synchronized findings to Feishu Group.
- Pushing to GitHub Blog `blog/polymarket_analysis/quantitative/2026-02-05-netflix-discrepancy.md`.
