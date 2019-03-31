<template>
    <div id="main">
        <p class="result-text1">为您找到相关结果约{{resultCounts}}条，用时{{resultTime}}</p>
        <p class="result-text2">以下为您显示“广东”的搜索结果。</p>
        <ul>
            <li>
                <p class="result-title mgb10 blue">广东省自贸办关于印发广东自贸试验区首批制</p>
                <p
                    class="result-content mgb10"
                >各地级以上市人民政府、顺德区政府，广东自贸试验区工作领导小组各成员单位： 2015年4月，中国（广东）自由贸易试验区（以下简称广东自贸试验区）挂牌运作以来，坚持以制度创新为核心，在投资便利化、贸易便利化......</p>
                <div class="result-info">
                    <span
                        class="result-url mgb10 green"
                    >http://www.china-gdftz.gov.cn/zwgk/tzgg/201811/t20181122_4612.html</span>
                    <span class="result-date">2015-12-28</span>
                </div>
            </li>
            <li>
                <p class="result-title mgb10 blue">广东省自贸办关于印发广东自贸试验区首批制</p>
                <p
                    class="result-content mgb10"
                >各地级以上市人民政府、顺德区政府，广东自贸试验区工作领导小组各成员单位： 2015年4月，中国（广东）自由贸易试验区（以下简称广东自贸试验区）挂牌运作以来，坚持以制度创新为核心，在投资便利化、贸易便利化......</p>
                <div class="result-info">
                    <span
                        class="result-url mgb10 green"
                    >http://www.china-gdftz.gov.cn/zwgk/tzgg/201811/t20181122_4612.html</span>
                    <span class="result-date">2015-12-28</span>
                </div>
            </li>
            <li>
                <p class="result-title mgb10 blue">广东省自贸办关于印发广东自贸试验区首批制</p>
                <p
                    class="result-content mgb10"
                >各地级以上市人民政府、顺德区政府，广东自贸试验区工作领导小组各成员单位： 2015年4月，中国（广东）自由贸易试验区（以下简称广东自贸试验区）挂牌运作以来，坚持以制度创新为核心，在投资便利化、贸易便利化......</p>
                <div class="result-info">
                    <span
                        class="result-url mgb10 green"
                    >http://www.china-gdftz.gov.cn/zwgk/tzgg/201811/t20181122_4612.html</span>
                    <span class="result-date">2015-12-28</span>
                </div>
            </li>
            <li>
                <p class="result-title mgb10 brand-color">广东省自贸办关于印发广东自贸试验区首批制</p>
                <p
                    class="result-content mgb10"
                >各地级以上市人民政府、顺德区政府，广东自贸试验区工作领导小组各成员单位： 2015年4月，中国（广东）自由贸易试验区（以下简称广东自贸试验区）挂牌运作以来，坚持以制度创新为核心，在投资便利化、贸易便利化......</p>
                <div class="result-info">
                    <span
                        class="result-url mgb10 green"
                    >http://www.china-gdftz.gov.cn/zwgk/tzgg/201811/t20181122_4612.html</span>
                    <span class="result-date">2015-12-28</span>
                </div>
            </li>
            <li>
                <p class="result-title mgb10 blue">广东省自贸办关于印发广东自贸试验区首批制</p>
                <p
                    class="result-content mgb10"
                >各地级以上市人民政府、顺德区政府，广东自贸试验区工作领导小组各成员单位： 2015年4月，中国（广东）自由贸易试验区（以下简称广东自贸试验区）挂牌运作以来，坚持以制度创新为核心，在投资便利化、贸易便利化......</p>
                <div class="result-info">
                    <span
                        class="result-url mgb10 green"
                    >http://www.china-gdftz.gov.cn/zwgk/tzgg/201811/t20181122_4612.html</span>
                    <span class="result-date">2015-12-28</span>
                </div>
            </li>
        </ul>
        <el-pagination background layout="prev, pager, next" class="page-item" :total="1000"></el-pagination>
    </div>
</template>

<script>
export default {
    name: "myMain",
    data() {
        return {
            resultCounts: "23333",
            resultTime: "2.3333333"
        };
    }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="stylus">
#main
    width 73%;
    border-top 1px solid grey;
    border-right 1px solid grey;
    padding 35px 30px 0px 30px;

    .result-text1
        color rgb(153, 153, 153);
        font-weight bold;
        text-align left;

    .result-text2
        font-weight bold;
        text-align left;
        margin-top 15px;
        width 100%;
        padding-bottom 10px;
        border-bottom 1px solid grey;

    li
        padding 30px 0px;
        text-align left;
        border-bottom 1px solid grey;

        .result-url
            border-bottom 1px solid rgb(125 173 72);

        .mgb10
            margin-bottom 10px;

        .green
            color rgb(125 173 72);

        .result-title
            font-size 18px;
            color rgb(64, 158, 255);

        .result-content
            font-size small;

        .result-info
            display flex;
            justify-content space-between;
            font-size 14px;
            margin-top 10px;

    .page-item
        margin-top 30px;
        margin-bottom 70px;
</style>
