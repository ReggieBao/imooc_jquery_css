# jQuery-
jquery-展示选择器的使用
同一层选择时不必既选择标签名又选择类名
eg:<div id="menu_con">
        <h3>男装</h3>
        <div class="tag" style="display:block">
            <dl>
                <dd>
                    <p>第一类</p>
                    
                </dd>
            </dl>
        </div>
        选择“第一类”时：$("menu_con .tag dd>p"),.tag之前不必再选择div
