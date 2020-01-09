---
title: conectividade
layout:  null
tab: true
order: 1
tags: conectividade-tag
---

## Conectividade e Midia Digital

**Ambiente de Desenvolvimento:** <http://github.com/OWASP-Cuiaba>
**Ambiente Educacional:** <http://github.com/OWASP-Cuiaba>
**Ambiente de Comunicação:** Server: irc.freenode.net. Canal:
    \#owasp_cuiaba

## Agenda Chapter Cuiabá
Acompanhe as atividades da comunidade pela adicione os eventos em sua
agenda. [Calendario Oficial](https://calendar.google.com/calendar/embed?src=owasp.org_2dlqbcecuri6ivgmhh041i61os%40group.calendar.google.com&ctz=America/Cuiaba)

<!-- Step 1: Link required files -->
link the format-google-calendar library

<!-- Step 2: Create HTML markup -->
<ul id="events-upcoming"></ul>
<ul id="events-past"></ul>

<!-- Step 3: Call the FormatGoogleCalendar -->
formatGoogleCalendar.init({
 calendarUrl: 'https://www.googleapis.com/calendar/v3/calendars/milan.kacurak@gmail.com/events?key=AIzaSyCR3-ptjHE-_douJsn8o20oRwkxt-zHStY',
 past: false,
 upcoming: true,
 sameDayTimes: true,
 dayNames: true,
 pastTopN: -1,
 upcomingTopN: 3,
 itemsTagName: 'li',
 upcomingSelector: '#events-upcoming',
 pastSelector: '#events-past',
 recurringEvents: true, 
 upcomingHeading: '<h2>Upcoming events</h2>',
 pastHeading: '<h2>Past events</h2>'
 format: ['*date*', ': ', '*summary*', ' — ', '*description*', ' in ', '*location*'],
 timeMin: '2016-06-03T10:00:00-07:00',
 timeMax: '2020-06-03T10:00:00-07:00'
});


<iframe src="https://calendar.google.com/calendar/b/2/embed?height=600&amp;wkst=1&amp;bgcolor=%23ffffff&amp;ctz=America%2FCuiaba&amp;src=a2VtYm9sbGVAb3dhc3Aub3Jn&amp;src=b3dhc3Aub3JnXzJkbHFiY2VjdXJpNml2Z21oaDA0MWk2MW9zQGdyb3VwLmNhbGVuZGFyLmdvb2dsZS5jb20&amp;src=ZW4uYnJhemlsaWFuI2hvbGlkYXlAZ3JvdXAudi5jYWxlbmRhci5nb29nbGUuY29t&amp;src=cHQuYnJhemlsaWFuI2hvbGlkYXlAZ3JvdXAudi5jYWxlbmRhci5nb29nbGUuY29t&amp;color=%23336699&amp;color=%23DD5511&amp;color=%235A9A08&amp;color=%23227F63" style="border:solid 1px #777" width="800" height="600" frameborder="0" scrolling="no"></iframe>
