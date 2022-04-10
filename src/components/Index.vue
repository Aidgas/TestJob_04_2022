<template>
    <div id="page">
        
        <div class="page-content">
            <h1 id="page-header-title">
                <span class="page-for-pc">Медицинские услуги</span>
                <span class="page-for-mobile">Мед. услуги</span>
            </h1>
        </div>
        
        <div id="page-slider-container">
            <!--<div id="page-slider">-->
            <Flicking :options="{ align: 'prev', horizontal: true, circular: true, circularFallback: 'bound' }">
                <div class="page-slider-item page-slider-item-bg1">
                    <div class="page-slider-item-header">
                        <span class="page-for-pc">Анализы дома</span>
                        <span class="page-for-mobile">Вызов бригады<br />домой</span>
                    </div>
                    <div class="page-slider-item-botyText">
                        Бесплатный выезд.<br/>Для детей и взрослых.<br/>Удобно и быстро.
                    </div>
                    <div class="page-slider-item-footer">
                        <span>Бесплатно</span>
                    </div>
                </div>
                <div class="page-slider-item page-slider-item-bg2">
                    <div class="page-slider-item-header">
                        МРТ
                    </div>
                    <div class="page-slider-item-botyText">
                        Запись на магнитно-<br/>резонансную томографию.<br/>8 видов скрининга.
                    </div>
                    <div class="page-slider-item-footer">
                        <span>От 1 690 Р</span>
                    </div>
                </div>
                <div class="page-slider-item page-slider-item-bg3">
                    <div class="page-slider-item-header">
                        Срочные<br/>анализы CITO
                    </div>
                    <div class="page-slider-item-botyText">
                        Быстрая диагностика<br/>в день обращения.<br/>Более 30 видов анализов.
                    </div>
                    <div class="page-slider-item-footer">
                        <span class="page-for-pc-inlineFlex">Результаты в 14:00</span>
                        <span class="page-for-mobile-inlineFlex">Найти отделение</span>
                    </div>
                </div>
            </Flicking>
            <!--</div>-->
        </div>
        
        <div class="page-content">
            <div id="page-other-services-title">Другие медицинские услуги</div>
            <div id="page-other-services-div">
                <div class="page-other-services-div-line">
                    <span class="page-other-services-div-line-main">УЗИ</span>
                    <span>УЗИ дома <label>– бесплатный выезд</label></span>
                    <span class="page-other-services-div-line-main">ЭКГ</span>
                    <span>ЭКГ дома <label>– бесплатный выезд</label></span>
                </div>
                <div class="page-other-services-div-line">
                    <span class="page-other-services-div-line-treatment-surgitron">Лечение Сургитрон</span>
                    <span class="page-other-services-div-line-colposcopy">Кольпоскопия</span>
                </div>
            </div>
            
            <div id="page-all-services-ref">
                <span class="page-for-pc">Все медицинские услуги Гемотест (35) →</span>
                <span class="page-for-mobile">Все медуслуги Гемотест (35) →</span>
            </div>
            <div id="page-footer-menu">
                <div class="page-footer-menu-item">
                    <img class="page-footer-menu-item-icon" src="/images/icon-1.svg" />
                    <div class="page-footer-menu-item-body">
                        <div class="page-for-pc">
                            <div class="page-footer-menu-item-body-title">Справка<br />в налоговую (ФНС)</div>
                            <div class="page-footer-menu-item-body-text">для оформления<br />налогового вычета</div>
                        </div>
                        <div class="page-for-mobile">
                            <div class="page-footer-menu-item-body-title">Справка в налоговую</div>
                            <div class="page-footer-menu-item-body-text">для оформления<br />налогового вычета</div>
                        </div>
                    </div>
                </div>
                <div class="page-footer-menu-item">
                    <img class="page-footer-menu-item-icon" src="/images/icon-2.svg" />
                    <div class="page-footer-menu-item-body">
                        <div class="page-for-pc">
                            <div class="page-footer-menu-item-body-title">Бесплатная<br />консультация</div>
                            <div class="page-footer-menu-item-body-text">врача Гемотест<br />по телефону</div>
                        </div>
                        <div class="page-for-mobile">
                            <div class="page-footer-menu-item-body-title">Бесплатная<br />консультация врача</div>
                            <div class="page-footer-menu-item-body-text">по телефону</div>
                        </div>
                    </div>
                </div>
                <div class="page-footer-menu-item">
                    <img class="page-footer-menu-item-icon" src="/images/icon-3.svg" />
                    <div class="page-footer-menu-item-body">
                        <div class="page-for-pc">
                            <div class="page-footer-menu-item-body-title">Расшифровка<br />результатов</div>
                            <div class="page-footer-menu-item-body-text">из других<br />лабораторий</div>
                        </div>
                        <div class="page-for-mobile">
                            <div class="page-footer-menu-item-body-title">Расшифровка<br />результатов</div>
                            <div class="page-footer-menu-item-body-text">из других лабораторий</div>
                        </div>
                    </div>
                </div>
                <div class="page-footer-menu-item">
                    <img class="page-footer-menu-item-icon" src="/images/icon-4.svg" />
                    <div class="page-footer-menu-item-body">
                        <div class="page-for-pc">
                            <div class="page-footer-menu-item-body-title">Бонусная<br />программа</div>
                            <div class="page-footer-menu-item-body-text">«Копите<br />на здоровье»</div>
                        </div>
                        <div class="page-for-mobile">
                            <div class="page-footer-menu-item-body-title">Бонусная программа</div>
                            <div class="page-footer-menu-item-body-text">«Копите<br />на здоровье»</div>
                        </div>
                    </div>
                </div>
                <div class="page-footer-menu-item">
                    <img class="page-footer-menu-item-icon" src="/images/icon-5.svg" />
                    <div class="page-footer-menu-item-body">
                        <div class="page-for-pc">
                            <div class="page-footer-menu-item-body-title">Второе мнение<br />в онкологии</div>
                            <div class="page-footer-menu-item-body-text">от экспертов<br />мирового уровня</div>
                        </div>
                        <div class="page-for-mobile">
                            <div class="page-footer-menu-item-body-title">Второе мнение<br />от онкоэкспертов</div>
                            <div class="page-footer-menu-item-body-text">мирового уровня</div>
                        </div>
                    </div>
                </div>
            </div>
            
        </div>
    </div>
</template>

<script>
    import Flicking from "@egjs/vue3-flicking";
    import "@egjs/vue3-flicking/dist/flicking.css";
    
    export default {
        components: {
            Flicking: Flicking
        }
    }
</script>

<style scoped>
    #page {
        padding: 40px 0;
    }
    .page-content {
        padding: 0 48px;
    }
    .page-for-mobile, .page-for-mobile-inlineFlex {
        display: none !important;
    }
    #page-header-title {
        font-style: normal;
        font-weight: 800;
        font-size: 30px;
        line-height: 36px;
        margin-top: 0;
        margin-bottom: 44px;
    }
    #page-slider-container {
        padding: 0 0 0 48px;
        width: 100%;
        margin-bottom: 48px;
    }
    #page-slider {
        margin-bottom: 48px;
        display: flex;
        align-items: flex-start;
        position: relative;
        overflow-y: hidden;
        overflow-x: auto;
    }
    .page-slider-item {
        width: 298.6px;
        min-width: 298.6px;
        height: 280px;
        display: flex;
        flex-direction: column;
        margin-right: 16px;
        padding: 32px 40px;
        border-radius: 5px; 
        overflow: hidden;
    }
    .page-slider-item-header {
        font-style: normal;
        font-weight: 600;
        font-size: 24px;
        line-height: 28px;
        color: #FFFFFF;
        height: 56px;
        margin-bottom: 20px;
    }
    .page-slider-item-botyText {
        font-style: normal;
        font-weight: 400;
        font-size: 16px;
        line-height: 24px;
        color: #FFFFFF;
        margin-bottom: 24px;
    }
    .page-slider-item-footer > span {
        background: #F26531;
        border-radius: 20px;
        display: inline-flex;
        align-items: center;
        justify-content: center;
        font-style: normal;
        font-weight: 600;
        font-size: 13px;
        line-height: 24px;
        color: #FFFFFF;
        padding: 0 18px 2px 18px;
        height: 31px;
        
    }
    
    .page-slider-item-bg1 {
        background: linear-gradient(228.47deg, rgba(242, 101, 49, 0.4) 9.44%, rgba(0, 121, 52, 0.4) 89.9%)
            , linear-gradient(0deg, rgba(41, 45, 58, 0.6)
            , rgba(41, 45, 58, 0.6))
            , no-repeat url(/images/slider-1.png);
        background-size: cover;
        background-position: center;
    }
    
    .page-slider-item-bg2 {
        background: linear-gradient(228.47deg, rgba(242, 101, 49, 0.4) 9.44%, rgba(0, 121, 52, 0.4) 89.9%)
            , linear-gradient(0deg, rgba(41, 45, 58, 0.6)
            , rgba(41, 45, 58, 0.6))
            , no-repeat url(/images/slider-2.png);
        background-size: cover;
        background-position: center;
    }
    
    .page-slider-item-bg3 {
        background: linear-gradient(228.47deg, rgba(242, 101, 49, 0.4) 9.44%, rgba(0, 121, 52, 0.4) 89.9%)
            , linear-gradient(0deg, rgba(41, 45, 58, 0.6)
            , rgba(41, 45, 58, 0.6))
            , no-repeat url(/images/slider-3.png);
        background-size: cover;
        background-position: center;
    }
    
    #page-other-services-title {
        text-transform: uppercase;
        font-style: normal;
        font-weight: 700;
        font-size: 11px;
        line-height: 13px;
        letter-spacing: 0.05em;
        color: #292D3A;
        opacity: 0.3;
        margin-bottom: 16px;
    }
    #page-other-services-div {
        margin-bottom: 20px;
    }
    .page-other-services-div-line {
        display: flex;
        flex-wrap: wrap;
        align-items: center;
    }
    .page-other-services-div-line > span {
        font-style: normal;
        font-weight: 400;
        font-size: 16px;
        line-height: 32px;
        color: #292D3A;
    }
    .page-other-services-div-line > span:before {
        content: "•";
        color: #bcbcbd;
        opacity: 0.3;
        display: inline-block;
        margin: 0 10px;
    }
    .page-other-services-div-line > span:first-child:before {
        display: none;
    }
    .page-other-services-div-line > span > label {
        color: #f26531;
    }
    #page-all-services-ref {
        font-style: normal;
        font-weight: 700;
        font-size: 16px;
        line-height: 19px;
        color: #007934;
        margin-bottom: 48px;
        cursor: pointer;
        text-decoration: none;
    }
    #page-all-services-ref:hover {
        color: #0c6231;
    }
    
    #page-footer-menu {
        display: flex;
        align-items: flex-start;
    }
    .page-footer-menu-item {
        display: flex;
        flex-direction: column;
        align-items: center;
        width: 185.6px;
        height: 264px;
        background: rgb(234, 202, 77, 0.07);
    }
    .page-footer-menu-item-icon {
        width: 80px;
        height: 80px;
        margin-top: 28px;
        margin-bottom: 20px;
    }
    .page-footer-menu-item-body {
        display: flex;
        flex-direction: column;
        align-items: center;
    }
    .page-footer-menu-item-body-title, .page-footer-menu-item-body-text {
        font-style: normal;
        font-weight: 400;
        font-size: 14px;
        line-height: 24px;
        text-align: center;
    }
    .page-footer-menu-item-body-title {
        color: #007934;
    }
    .page-footer-menu-item:nth-child(odd) {
        background: rgb(234, 202, 77, 0.15);
    }
    
    @media screen and (max-width: 1024px) {
        .page-content {
            padding: 0 32px;
        }
    }
    
    @media screen and (max-width: 992px) {
        .page-footer-menu-item {
            width: 100%;
            height: 240px;
        }
        .page-footer-menu-item-icon {
            width: 72px;
            height: 72px;
            margin-top: 24px;
            margin-bottom: 12px;
        }
        .page-footer-menu-item-body-title, .page-footer-menu-item-body-text {
            font-size: 12px;
            line-height: 20px;
            text-align: center;
        }
        .page-slider-item {
            width: 216px;
            height: 240px;
            padding: 28px 32px;
        }
        .page-slider-item-header {
            font-size: 15px;
            line-height: 20px;
            margin-bottom: 16px;
        }
        .page-slider-item-botyText {
            font-size: 12px;
            line-height: 20px;
        }
        .page-slider-item-footer > span {
            font-size: 13px;
        }
    }
    
    @media screen and (max-width: 768px) {
        #page-footer-menu {
            flex-direction: column;
        }
        .page-footer-menu-item {
            flex-direction: row;
            width: 100%;
            height: 104px;
            padding: 16px 12px;
        }
        .page-footer-menu-item-icon {
            margin: 0;
            display: inline-block;
            margin-right: 12px;
        }
        .page-for-pc {
            display: none !important;
        }
        .page-for-mobile {
            display: block !important;
        }
        .page-for-pc-inlineFlex {
            display: none !important;
        }
        .page-for-mobile-inlineFlex {
            display: inline-flex !important;
        }
        .page-footer-menu-item-body-title, .page-footer-menu-item-body-text {
            text-align: left;
        }
        #page-all-services-ref {
            font-size: 13px;
            line-height: 16px;
        }
        .page-other-services-div-line > span {
            font-size: 13px;
            line-height: 28px;
        }
        #page-other-services-title {
            font-size: 10px;
            line-height: 12px;
            letter-spacing: normal;
            opacity: 0.2;
            margin-bottom: 20px;
        }
        #page-header-title {
            font-size: 20px;
            line-height: 24px;
            margin-bottom: 28px;
        }
        #page-all-services-ref {
            margin-bottom: 32px;
        }
        #page-slider-container {
            margin-bottom: 32px;
        }
        #page {
            padding: 20px 0;
        }
        #page-slider-container {
            padding-left: 32px;
        }
        .page-slider-item {
            margin-right: 8px;
        }
    }
    @media screen and (max-width: 590px) {
        .page-other-services-div-line-main {
            display: none;
        }
        .page-other-services-div-line > span:before {
            display: none;
        }
        .page-other-services-div-line {
            flex-direction: column;
            align-items: flex-start;
        }
        .page-other-services-div-line-colposcopy {
            order: 0;
        }
        .page-other-services-div-line-treatment-surgitron {
            order: 1;
        }
    }
</style>

