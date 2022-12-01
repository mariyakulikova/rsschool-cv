# Kulikova Mariya

### contacts:
**Email:** mariya.kulikova818@gmail.com \
**Expected Position:** Frontend developer 

### work experience:
#### April 2022 — August 2022
_Company:_ **Platrum** \
_Position:_ **Frontend developer** 

**My duties included:**
- developing new features for Platrum modules;
- programming the business logic of the client side of the applications;
- Integration with backend through REST-API;
- Collaboration with product manager, frontend and backend developers;
- Bug fixes. 

#### February 2021 — April 2022
_Company:_ **Aeronavigator** \
_position:_ **Frontend developer** 

**My duties included:**
- development from scratch and refinement of the visual part of business applications;
- programming the business logic of the client side of applications;
- integration with backend through REST-API;
- layout;
- collaboration with product manager, frontend and backend developers;
- bug fixes.

### Code example
```javascript
function bingo(ticket, win) {
    return ticket.reduce((winCount, currTicket) => {
        let isTicketWin = 0;

        for (let i = 0; i < currTicket[0].length; i++) {
            if (currTicket[0].charCodeAt(i) === currTicket[1]) {
                isTicketWin = 1;
            }
        }

        return winCount + isTicketWin;
    }, 0) >= win ? 'Winner!' : 'Loser!';
}
```
### Education
* MSU MAMI - management of machine manufacturing
* [Tinkoff Fintech School](https://fintech.tinkoff.ru/) - frontend dev course
* [Route256](https://route256.ozon.ru/frontend) - frontend dev course
* [School21](https://21-school.ru/) - swam the pool
