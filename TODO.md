# Task: Owner Panel and Advanced Features Implementation

## Completed
- [x] Database schema updates
  - [x] Created custom_roles table
  - [x] Created custom_ranks table with coin rewards
  - [x] Created flash_sales table
  - [x] Added coins_price and external_link to products
  - [x] Added top_players_visible to site_settings
  - [x] Created buy_with_coins and buy_rank_with_coins functions
- [x] Removed AFK system
  - [x] Deleted AfkRewardDialog component
  - [x] Removed AFK button from HomePage
  - [x] Removed AFK coin references from rank cards
- [x] Changed store name from "Robin Store" to "MineMart"
  - [x] Updated all component references
  - [x] Updated database site_settings
- [x] Updated types for new features
  - [x] Added CustomRole, CustomRank, FlashSale interfaces
  - [x] Updated Product with coins_price and external_link
  - [x] Updated SiteSettings with top_players_visible
- [x] Added API functions
  - [x] Custom roles CRUD
  - [x] Custom ranks CRUD
  - [x] Flash sales CRUD
  - [x] Top players analytics
  - [x] Buy with coins functions
- [x] Updated ProductsManagement
  - [x] Added coins_price field
  - [x] Added external_link field
- [x] Created Owner Panel page
  - [x] Role management UI
  - [x] Rank management UI with coin rewards configuration
  - [x] Owner-only access check
  - [x] Added route and header link

## Pending (Future Enhancements)
- [ ] Create Flash Sale management component in Admin Panel
  - [ ] Product selection
  - [ ] Discount configuration
  - [ ] Activate/deactivate toggle
  - [ ] Custom name input
- [ ] Create Analytics Dashboard in Owner Panel
  - [ ] Top players by coins (live)
  - [ ] Display statistics
- [ ] Create Top Players public display on HomePage
  - [ ] Leaderboard component
  - [ ] Toggle visibility setting
- [ ] Update ProductCard component
  - [ ] Show coins_price option
  - [ ] Handle external_link (open in new tab)
  - [ ] Handle file_url (download)
  - [ ] Buy with coins button
- [ ] Update RankCard/Ranks display on HomePage
  - [ ] Show coins_price option
  - [ ] Buy with coins button
  - [ ] Dynamic rank loading from custom_ranks
- [ ] Apply flash sale discounts to products
- [ ] Test all new features end-to-end

## Notes
- Owner is identified as the first user (by created_at)
- Flash sales can have custom names
- Products can have both INR price and coins price
- External links take priority over file downloads
- Top players leaderboard should update in real-time
- All core database structures and API functions are in place
- Owner Panel is functional for role and rank management
- Daily rewards now use custom_ranks table for coin amounts
