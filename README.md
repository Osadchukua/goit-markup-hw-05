1) 1:33 - що саме тут доробити? (outline: transparent;)
Чи можете показати?

2) Добавив посилання
https://prnt.sc/-Kz1ftbp1SaT
питання 
чи потрібен - "display: block" в

.gellery-link{
    display: block;
}

3) Чи я правильно добавив "opacity"
.portfolio-text-hover {
    <!-- position: absolute;
    top: 0;
    left: 0;
    font-size: 18px;
    line-height: 1.56;
    letter-spacing: 0.03em;
    color: var(--hero-title-color);
    padding: 63px 24px 0px 24px;
    background: rgba(33, 150, 243, 0.9);
    height: 100%; -->
    opacity: 1;
    transform: translateY(100%);
    transition: transform var(--transition-duration) var(--timig-function), 
    opacity var(--transition-duration) var(--timig-function);
}

4) Калькуляцію поправив