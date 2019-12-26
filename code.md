```JavaScript
var today = new Date();
var nowHour = today.getHours() + 8;
var nowMinute = today.getMinutes();
var nowTimeEmoji;
switch (nowHour) {
    case 0:
        if (nowMinute >= 0 && nowMinute < 15) {
            nowTimeEmoji = "🕛";
        } else if (nowMinute >= 15 && nowMinute < 45) {
            nowTimeEmoji = "🕧";
        } else if (nowMinute >= 45 && nowMinute < 60) {
            nowTimeEmoji = "🕐";
        }
        break;
    case 1:
        if (nowMinute >= 0 && nowMinute < 15) {
            nowTimeEmoji = "🕐";
        } else if (nowMinute >= 15 && nowMinute < 45) {
            nowTimeEmoji = "🕜";
        } else if (nowMinute >= 45 && nowMinute < 60) {
            nowTimeEmoji = "🕑";
        }
        break;
    case 2:
        if (nowMinute >= 0 && nowMinute < 15) {
            nowTimeEmoji = "🕑";
        } else if (nowMinute >= 15 && nowMinute < 45) {
            nowTimeEmoji = "🕝";
        } else if (nowMinute >= 45 && nowMinute < 60) {
            nowTimeEmoji = "🕒";
        }
        break;
    case 3:
        if (nowMinute >= 0 && nowMinute < 15) {
            nowTimeEmoji = "🕒";
        } else if (nowMinute >= 15 && nowMinute < 45) {
            nowTimeEmoji = "🕞";
        } else if (nowMinute >= 45 && nowMinute < 60) {
            nowTimeEmoji = "🕓";
        }
        break;
    case 4:
        if (nowMinute >= 0 && nowMinute < 15) {
            nowTimeEmoji = "🕓";
        } else if (nowMinute >= 15 && nowMinute < 45) {
            nowTimeEmoji = "🕟";
        } else if (nowMinute >= 45 && nowMinute < 60) {
            nowTimeEmoji = "🕔";
        }
        break;
    case 5:
        if (nowMinute >= 0 && nowMinute < 15) {
            nowTimeEmoji = "🕔";
        } else if (nowMinute >= 15 && nowMinute < 45) {
            nowTimeEmoji = "🕠";
        } else if (nowMinute >= 45 && nowMinute < 60) {
            nowTimeEmoji = "🕕";
        }
        break;
    case 6:
        if (nowMinute >= 0 && nowMinute < 15) {
            nowTimeEmoji = "🕕";
        } else if (nowMinute >= 15 && nowMinute < 45) {
            nowTimeEmoji = "🕡";
        } else if (nowMinute >= 45 && nowMinute < 60) {
            nowTimeEmoji = "🕖";
        }
        break;
    case 7:
        if (nowMinute >= 0 && nowMinute < 15) {
            nowTimeEmoji = "🕖";
        } else if (nowMinute >= 15 && nowMinute < 45) {
            nowTimeEmoji = "🕢";
        } else if (nowMinute >= 45 && nowMinute < 60) {
            nowTimeEmoji = "🕗";
        }
        break;
    case 8:
        if (nowMinute >= 0 && nowMinute < 15) {
            nowTimeEmoji = "🕗";
        } else if (nowMinute >= 15 && nowMinute < 45) {
            nowTimeEmoji = "🕣";
        } else if (nowMinute >= 45 && nowMinute < 60) {
            nowTimeEmoji = "🕘";
        }
        break;
    case 9:
        if (nowMinute >= 0 && nowMinute < 15) {
            nowTimeEmoji = "🕘";
        } else if (nowMinute >= 15 && nowMinute < 45) {
            nowTimeEmoji = "🕤";
        } else if (nowMinute >= 45 && nowMinute < 60) {
            nowTimeEmoji = "🕙";
        }
        break;
    case 10:
        if (nowMinute >= 0 && nowMinute < 15) {
            nowTimeEmoji = "🕙";
        } else if (nowMinute >= 15 && nowMinute < 45) {
            nowTimeEmoji = "🕥";
        } else if (nowMinute >= 45 && nowMinute < 60) {
            nowTimeEmoji = "🕚";
        }
        break;
    case 11:
        if (nowMinute >= 0 && nowMinute < 15) {
            nowTimeEmoji = "🕚";
        } else if (nowMinute >= 15 && nowMinute < 45) {
            nowTimeEmoji = "🕦";
        } else if (nowMinute >= 45 && nowMinute < 60) {
            nowTimeEmoji = "🕛";
        }
        break;
    case 12:
        if (nowMinute >= 0 && nowMinute < 15) {
            nowTimeEmoji = "🕛";
        } else if (nowMinute >= 15 && nowMinute < 45) {
            nowTimeEmoji = "🕧";
        } else if (nowMinute >= 45 && nowMinute < 60) {
            nowTimeEmoji = "🕐";
        }
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
