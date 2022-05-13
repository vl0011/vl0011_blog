<div class="cat-item">
    <div class="cat-header">
        <span class="cat-header-title">css</span>
        <span class="cat-header-articles">
            5 articles
        </span>
    </div>
    <ul class="cat-item-list">
        <li class="cat-item-list-item">
            <a class="cat-item-list-link">
                <span class="cat-item-list-icon"></span>
                글 A
            </a>
        </li>
        <li class="cat-item-list-item">
            <a class="cat-item-list-link">
                <span class="cat-item-list-icon"></span>
                글 B
            </a>
        </li>
        <li class="cat-item-list-item">
            <a class="cat-item-list-link">
                <span class="cat-item-list-icon"></span>
                글 C
            </a>
        </li>
        <li class="cat-item-list-item">
            <a class="cat-item-list-link">
                <span class="cat-item-list-icon"></span>
                글 D
            </a>
        </li>
        <li class="cat-item-list-item">
            <a class="cat-item-list-link">
                <span class="cat-item-list-icon"></span>
                글 B
            </a>
        </li>
    </ul>
    <a class="cat-item-view-more">
        VIEW ALL
    </a>
</div>

<style>
    .cat-item {
        flex: 1 1 40%;
        position: relative;
        margin-left: 20px;
        margin-right: 20px;
        /*height: 200px;*/
        /*min-height: 250px;*/
        margin-bottom: 20px;
    }

    .cat-header {
        border-bottom: 1px solid var(--primary-color);
        padding-bottom: 5px;
    }

    .cat-header-title {
        font-size: 20px;
        padding-left: 5px;
    }

    .cat-header-articles {
        color: var(--primary-color);
        padding-left: 5px;
    }

    .cat-item-list {
        list-style: none;
        padding-left: 0;
    }

    .cat-item-list-link {
        text-decoration: none;
        display: flex;
        border-bottom: 1px solid var(--pure-white);
    }

    .cat-item-list-link:hover {
        border-bottom: 1px solid var(--primary-color);
    }

    .cat-item-list-icon:before {
        content: "-";
        margin-right: 5px;
    }

    .cat-item-list-icon {
        margin-right: 2px;
    }

    .cat-item-view-more {
        color: var(--primary-color);
        font-size: 15px;
        display: flex;
    }

    .cat-item-view-more::after {
        content: "➜";
        margin-left: 5px;
    }

    .cat-item-list-item {
        margin-bottom: 8px;
    }

</style>

<script>

</script>