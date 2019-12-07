```JavaScript
var today = new Date();
var nowHour = today.getHours() + 8;
var nowMinute = today.getMinutes();
var nowTimeEmoji;
switch (nowHour) {
    case 0, 12:
        nowTimeEmoji = (nowMinute > 15 && nowMinute < 45) ? "🕧" : "🕛";
        break;
    case 1, 13:
        nowTimeEmoji = (nowMinute > 15 && nowMinute < 45) ? "🕜" : "🕐";
        break;
    case 2, 14:
        nowTimeEmoji = (nowMinute > 15 && nowMinute < 45) ? "🕝" : "🕑";
        break;
    case 3, 15:
        nowTimeEmoji = (nowMinute > 15 && nowMinute < 45) ? "🕞" : "🕒";
        break;
    case 4, 16:
        nowTimeEmoji = (nowMinute > 15 && nowMinute < 45) ? "🕟" : "🕓";
        break;
    case 5, 17:
        nowTimeEmoji = (nowMinute > 15 && nowMinute < 45) ? "🕠" : "🕔";
        break;
    case 6, 18:
        nowTimeEmoji = (nowMinute > 15 && nowMinute < 45) ? "🕡" : "🕕";
        break;
    case 7, 19:
        nowTimeEmoji = (nowMinute > 15 && nowMinute < 45) ? "🕢" : "🕖";
        break;
    case 8, 20:
        nowTimeEmoji = (nowMinute > 15 && nowMinute < 45) ? "🕣" : "🕗";
        break;
    case 9, 21:
        nowTimeEmoji = (nowMinute > 15 && nowMinute < 45) ? "🕤" : "🕘";
        break;
    case 10, 22:
        nowTimeEmoji = (nowMinute > 15 && nowMinute < 45) ? "🕥" : "🕙";
        break;
    case 11, 23:
        nowTimeEmoji = (nowMinute > 15 && nowMinute < 45) ? "🕦" : "🕚";
        break;
}
var currentDateTime =
    today.getFullYear() + 'Year' +
    (today.getMonth() + 1) + 'Month' +
    today.getDate() + '.（' +
    nowTimeEmoji + nowHour + ':' + nowMinute +
    '）';
var hour = today.getHours();
agent.add("Now is:" + currentDateTime);
```
