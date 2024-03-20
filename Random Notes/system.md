// 0 SW_ENTRY_NO
// 1 SW_BGM_NO
// 3 battle result 
// 4 current chapter 
// 10 party lead 
// 11 party second 
// 12 party third 
// 13 party fourth 
// 14 party fifth (guest) 
// 15 party sixth (guest) 
// 18 current mira 
// 19 ItemId used in item handler 
// 21 number of battles 
// 26 used much during the Madrigal, and when Joshua is activated in SC. 
// 27 Boolean. Often set together with 26. 
// 35 set to 255 once after rescuing Tita in FC 
// 28 Boolean. Generally only set to true for a short time 
// 40 SW_CURSOR_FORM (24 MSCRS_NORMAL, FFFF MSCRS_VOID) 
// 41 BattleId, generally checked in reinit 
// 42 sometimes set to a negative number in reinit. I suspect it's something with altitude. 
// 43 set to 255 in some reinit in FC 
// 45 SW_MOVIE_STATE 
// 46 CharId, set together with 26 and 27 in the Madrogal. Spotlight character? 
// 47 Bracer rank
// 49 TownId for the next save, values include 19, 140, 302, 400, 401, 274, 259, 297, 296, 299