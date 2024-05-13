# contact us

<style>
    .container {
        display: flex;
        flex-direction: column;
        align-items: center;
        padding: 0 20px; /* 减少水平内边距，适应小屏幕 */
    }

    .item {
        margin-bottom: 20px; /* 增加垂直间距 */
        text-align: center; /* 文字居中 */
    }

    .item img {
        width: 80%;
        max-width: 300px; /* 设置图像最大宽度 */
    }

    .item p {
        font-size: 18px;
    }

    @media (min-width: 768px) {
        .container {
            flex-direction: row;
            justify-content: space-between;
            padding: 0 200px;
        }

        .item {
            margin-bottom: 0; /* 在大屏幕上取消垂直间距 */
        }
    }
</style>

<div class="container">
    <div class="item">
        <img src="_media/twitter.jpg">
        <p>Twitter</p>
    </div>
    <div class="item">
        <img src="_media/youtube.jpg">
        <p>YouTube</p>
    </div>
    <div class="item">
        <img src="_media/wechat.jpg">
        <p>WeChat</p>
    </div>
</div>

<div class="container">
    <div class="contact-info">
        <div>
            <img src="_media/mail.ico">
            <a href="mailto:contact@arx-x.com">contact@arx-x.com</a>
        </div>
        <div>
            <img src="_media/twitter.ico">
            <a href="https://twitter.com/ARX_Zhang">https://twitter.com/ARX_Zhang</a>
        </div>
        <div>
            <img src="_media/youtube.ico">
            <a href="https://www.youtube.com/@ARX-unlimited">https://www.youtube.com/@ARX-unlimited</a>
        </div>
    </div>
</div>
