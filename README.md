# lets_HTML
## day 1
0. additional information about HTML elements called ATTRIBUTE
1. *lang attribute declared language(en), dialect(US)*
2. *style attribute syntax: "property:value;"*
3. *hr tag: 구분선*
4. *title attribute:tooltip when mouse over the paragraph*
5. *pre tag: preformatted text*
6. *img tag: src(source file), alt(alternative text/묘사)*
7. *blockquote tag는 줄바꿈을 인식함*
8. *abbreviation for giving info to browsers, translation systems, search-engines*
9. **쓸모 없어 보이는 태그도 용도가 다 있다**

## day 2
1. *Color Values_RGB Value: rgb(red, green, blue) / HEX Value: #rrggbb / HSL Value: hsl(hue, saturation, lightness), hue=rgb, saturation=채도, lightness=명도 / RGBA Value: rgba(red, green, blue, alpha) / hsla(hue, saturation, lightness, alpha*
2. *head 태그 안에 style 태그로 css 가능(internal), link rel="stylesheet" href="styles.css" 태그(external)*
3. *CSS padding: 여유 공간(안쪽) / CSS Margin(다른 element 사이)*
4. *id를 설정하면 css에서 활용 가능(#), class 설정도 가능 (태그.클래스)*
5. *Without a forward slash at the end of subfolder addresses, you might generate two requests to the server. Many servers will automatically add a forward slash to the end of the address, and then create a new request.*
6. *local link: link to the same web site*
7. *css를 사용하면 link, visited, hover, active의 색깔 변경 가능*
8. *link-target attribute: _blank(새창, 새탭), _self(default, 같은 창(탭)), _parent(parent 창(상위 창)), _top(최상위 창), frame name(지정된 창)*
9. *북마크 만드는 법: id 추가 후 href="#id"(same page), href="html_demo.html*id"(another page)*

## day 3
1. *image element의 width와 height는 style attribute로 컨트롤하는 게 좋음*
2. *image float: 본문 안에 이미지 배치*
3. *div / span: 블럭 단위, 또는 inline element에 style, class, id*
4. *class(.)와 id(#)의 차이점: class는 여러번 사용 가능! id는 한번만*
5. *class를 여러개 줄 때는 띄어쓰기로 구분*
6. *class, id를 CSS와 JavaScript에서(getElementsByClassName(), getElementById()) 사용*
7. *viewport element를 포함하면 장치마다 맞춤 view 제공 가능 (반응형 웹) + style="(max-)width:100%;height:auto;font-size:10vw" + picture element(?) + Media Queries + CSS + Bootstrap*
8. *base 태그로 기본 url과 target default를 설정*
9. *Layout(semantic elements): header, nav, section, article, aside, footer, details, summary, details*
10. *input type: text, password, submit, reset, radio, checkbox, button, color, date, datetime-local, email, month, number, range, search, tel, time, url, week*
11. *input attribute: value, readonly, disabled, size, maxlength, autocomplete, autofocus, form(form태그 밖에서 포함), formaction, formenctype(post방식에서 data 인코딩 방식), formmethod(form의 method보다 우선됨), formnovalidated, formtarget, height and width, list, min and max, multiple, pattern(regexp), placeholder, required, step(input에 화살표를 누를 때마다 증감되는 크기)*
12. *form attribute: autocomplete, novalidate(유효성 검증x)*
13. *createElement 가능*
14. **HTML5Shiv?**
15. *plug-ins: object, embed*
16. *iframe 태그로 youtube*

# lets_CSS
## day 4
1. *margin collapse: 같은 공간(사이)에 대해 다른 margin값을 지정한 두개의 element가 있다면 최대값 적용, inherit을 통해 같은 값을 적용 가능*
2. *width를 %로 지정 가능 (창에 대한 비율), max-width*
3. *content<padding<border<(outline-offset<)outline<margin*
4. *text-align: justify; (양옆 맞춤)*
5. *Font Awesome Icons: <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">*
6. *link는 4개의 상태를 가짐: a:link, a:visited, a:hover, a:active*

## day 5
1. *div style="overflow-x:auto;" around the table element -> responsive*
2. *display: inline(default, 높이넓이 무시, 글자처럼 취급), block(줄바꿈o, 높이넓이 적용), inline-block(높이넓이 적용, 글자처럼 취급)*
3. *position: static, relative, fixed, absolute(be positioned relative to the nearest positioned ancestor), sticky*
4. *z-index: layer(숫자가 작을수록(-1) 뒤에 배치)*
5. *clear: float를 무시하게 해주는 기능,* **clearfix?(::after)**
6. **Selector?**

## day 6
1. *descendant selector: div p (div element 안에 있는 모든 p), child selector: div>p (div element의 immediate children p), adjacent sibling selector: div+p (div element 바로 다음의 p만(div 제외)), general sibling selector: div~p (div element의 뒤에 존재하는 모든 sibling p (앞과 div 제외))*
2. *pseudo-classes: define a special state of an element*
3. *div:hover p{} (div위에 마우스가 가면 p의 style 변경)*