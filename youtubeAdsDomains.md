||youtube.com/api/pagead?
||youtube.com/api/stats/qoe?
||youtube.com/api/stats/playback?
||youtube.com/get_video?
||youtube.com/ptracking?
||youtube.com/api/stats/watchtime?
||youtube.com/youtubei/v1/log_event?
||youtube-nocookie.com/api/stats/atr?
||youtube-nocookie.com/api/stats/delayplay?
||youtube-nocookie.com/api/stats/qoe?
||youtube-nocookie.com/ptracking?
||youtube-nocookie.com/robots.txt?
||youtube-nocookie.com/api/stats/watchtime?
||youtube-nocookie.com/youtubei/v1/log_event?
||play.google.com/log
www.youtube.com##+js(trusted-replace-xhr-response, /"adPlacements.*?([A-Z]"\}|"\}{2\,4})\}\]\,/, , /playlist\?list=|player\?|watch\?v=|youtubei\/v1\/player/)
www.youtube.com##+js(trusted-replace-xhr-response, /"adPlacements.*?("adSlots"|"adBreakHeartbeatParams")/gms, $1, youtubei/v1/player)
www.youtube.com##+js(trusted-replace-fetch-response, /"adPlacements.*?([A-Z]"\}|"\}{2\,4})\}\]\,/, , player?)
www.youtube.com##+js(trusted-replace-fetch-response, /\"adSlots.*?\}\]\}\}\]\,/, , player?)
||www.youtube.com/playlist?list=$xhr,1p,replace=/"adPlacements.*?([A-Z]"\}|"\}{2\,4})\}\]\,//
||www.youtube.com/playlist?list=$xhr,1p,replace=/"adSlots.*?\}\]\}\}\]\,//
||www.youtube.com/watch?v=$doc,xhr,1p,replace=/"adPlacements.*?([A-Z]"\}|"\}{2\,4})\}\]\,//
||www.youtube.com/watch?v=$doc,xhr,1p,replace=/"adSlots.*?\}\]\}\}\]\,//
||www.youtube.com/youtubei/v1/player?$xhr,1p,replace=/"adPlacements.*?([A-Z]"\}|"\}{2\,4})\}\]\,//
||www.youtube.com/youtubei/v1/player?$xhr,1p,replace=/"adSlots.*?\}\]\}\}\]\,//
||www.youtube.com/playlist?list=$xhr,1p,replace=/"auxiliaryUi":\{"messageRenderers":\{"bkaEnforcementMessageViewModel.*?e\}\}\}\,//
||www.youtube.com/playlist?list=$xhr,1p,replace=/("trackingParam":"kx_fmPxhoPZR)[-_0-9A-Za-z]{150}[-_0-9A-Za-z]+?([-_0-9A-Za-z]{55}lLKPQ-SS"\})/\$1\$2/
||www.youtube.com/playlist?list=$xhr,1p,replace=/("trackingParam":"k5DfmPxhoXpR)[-_0-9A-Za-z]{150}[-_0-9A-Za-z]+?([-_0-9A-Za-z]{151}lLKPQGiS"\})/\$1\$2/
||www.youtube.com/watch?v=$doc,xhr,1p,replace=/"auxiliaryUi":\{"messageRenderers":\{"bkaEnforcementMessageViewModel.*?e\}\}\}\,//
||www.youtube.com/watch?v=$doc,xhr,1p,replace=/("trackingParam":"kx_fmPxhoPZR)[-_0-9A-Za-z]{150}[-_0-9A-Za-z]+?([-_0-9A-Za-z]{55}lLKPQ-SS"\})/\$1\$2/
||www.youtube.com/watch?v=$doc,xhr,1p,replace=/("trackingParam":"k5DfmPxhoXpR)[-_0-9A-Za-z]{150}[-_0-9A-Za-z]+?([-_0-9A-Za-z]{151}lLKPQGiS"\})/\$1\$2/
||www.youtube.com/youtubei/v1/player?$xhr,1p,replace=/"auxiliaryUi":\{"messageRenderers":\{"bkaEnforcementMessageViewModel.*?e\}\}\}\,//
||www.youtube.com/youtubei/v1/player?$xhr,1p,replace=/("trackingParam":"kx_fmPxhoPZR)[-_0-9A-Za-z]{150}[-_0-9A-Za-z]+?([-_0-9A-Za-z]{55}lLKPQ-SS"\})/\$1\$2/
||www.youtube.com/youtubei/v1/player?$xhr,1p,replace=/("trackingParam":"k5DfmPxhoXpR)[-_0-9A-Za-z]{150}[-_0-9A-Za-z]+?([-_0-9A-Za-z]{151}lLKPQGiS"\})/\$1\$2/
!/r\d+[\-]*sn-[a-z0-9\-]+\.googlevideo\.com/