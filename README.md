# UNI-INGAME-DARK-WHITE

Чтобы установить данный шаблон:

1.Загрузите в репозиторий с шаблонами папку ingame-dark-white
2.Перейдите в корневую папку движка modules_extra и замените в каждой папке ../template/standart на ../template/ingame-dark-white
3.В каждом файле index.tpl в modules_extra замените код или добавьте 
-----------------------------------------------
<div class="col-lg-3 order-is-last">
	{include file="/parts/mini-profile.tpl"}

	{include file="/parts/sidebar.tpl"}
</div>
-----------------------------------------------

Некоторые модули могут встать криво, но ничего страшного, знающий человек основы php html сможет настроить шаблон под себя!
