| クラス | フィールド | 説明 |
|:---|:---|:---|
|[BindingCollection](/javascript/api/excel/excel.bindingcollection)|[getCount()](/javascript/api/excel/excel.bindingcollection#getcount--)|コレクションに含まれるバインドの数を取得します。|
||[getItemOrNullObject(id: string)](/javascript/api/excel/excel.bindingcollection#getitemornullobject-id-)|ID を使用してバインド オブジェクトを取得します。|
|[ChartCollection](/javascript/api/excel/excel.chartcollection)|[getCount()](/javascript/api/excel/excel.chartcollection#getcount--)|ワークシート上のグラフの数を返します。|
||[getItemOrNullObject(name: string)](/javascript/api/excel/excel.chartcollection#getitemornullobject-name-)|グラフ名を使用してグラフを取得します。|
|[ChartPointsCollection](/javascript/api/excel/excel.chartpointscollection)|[getCount()](/javascript/api/excel/excel.chartpointscollection#getcount--)|系列に含まれるグラフのポイントの数を返します。|
|[ChartSeriesCollection](/javascript/api/excel/excel.chartseriescollection)|[getCount()](/javascript/api/excel/excel.chartseriescollection#getcount--)|コレクションに含まれるデータ系列の数を返します。|
|[NamedItem](/javascript/api/excel/excel.nameditem)|[comment](/javascript/api/excel/excel.nameditem#comment)|この名前に関連付けられているコメントを指定します。|
||[delete()](/javascript/api/excel/excel.nameditem#delete--)|指定された名前を削除します。|
||[getRangeOrNullObject()](/javascript/api/excel/excel.nameditem#getrangeornullobject--)|名前に関連付けられている範囲オブジェクトを返します。|
||[scope](/javascript/api/excel/excel.nameditem#scope)|ブックまたは特定のワークシートに対して、名前をスコープ設定するかどうかを指定します。|
||[worksheet](/javascript/api/excel/excel.nameditem#worksheet)|名前付きのアイテムの対象になるワークシートを返します。|
||[worksheetOrNullObject](/javascript/api/excel/excel.nameditem#worksheetornullobject)|名前付きのアイテムの対象になるワークシートを返します。|
|[NamedItemCollection](/javascript/api/excel/excel.nameditemcollection)|[add (name: string, reference: Range \| string, comment?: string)](/javascript/api/excel/excel.nameditemcollection#add-name--reference--comment-)|指定のスコープのコレクションに新しい名前を追加します。|
||[addFormulaLocal (name: string, formula: string, comment?: string)](/javascript/api/excel/excel.nameditemcollection#addformulalocal-name--formula--comment-)|ユーザーのロケールを数式に使用して、指定のスコープのコレクションに新しい名前を追加します。|
||[getCount()](/javascript/api/excel/excel.nameditemcollection#getcount--)|コレクションに含まれる名前付きアイテムの数を取得します。|
||[getItemOrNullObject(name: string)](/javascript/api/excel/excel.nameditemcollection#getitemornullobject-name-)|名前を使用して、NamedItem オブジェクトを取得します。|
|[PivotTableCollection](/javascript/api/excel/excel.pivottablecollection)|[getCount()](/javascript/api/excel/excel.pivottablecollection#getcount--)|コレクションに含まれるピボット テーブルの数を取得します。|
||[getItemOrNullObject(name: string)](/javascript/api/excel/excel.pivottablecollection#getitemornullobject-name-)|名前に基づいてピボットテーブルを取得します。|
|[Range](/javascript/api/excel/excel.range)|[getIntersectionOrNullObject (anotherRange: Range \| 文字列)](/javascript/api/excel/excel.range#getintersectionornullobject-anotherrange-)|指定した範囲の長方形の交差を表す範囲オブジェクトを取得します。|
||[getUsedRangeOrNullObject (パラメーターの設定のみ?: boolean)](/javascript/api/excel/excel.range#getusedrangeornullobject-valuesonly-)|指定した範囲オブジェクトのうち使用されている範囲を返します。|
|[RangeViewCollection](/javascript/api/excel/excel.rangeviewcollection)|[getCount()](/javascript/api/excel/excel.rangeviewcollection#getcount--)|コレクションに含まれる RangeView オブジェクトの数を取得します。|
|[設定](/javascript/api/excel/excel.setting)|[delete()](/javascript/api/excel/excel.setting#delete--)|設定を削除します。|
||[key](/javascript/api/excel/excel.setting#key)|設定の id を表すキー。|
||[value](/javascript/api/excel/excel.setting#value)|この設定に格納されている値を表します。|
|[SettingCollection](/javascript/api/excel/excel.settingcollection)|[add (key: string, value: string \| number \| boolean \| Date \| Array <any> \| any)](/javascript/api/excel/excel.settingcollection#add-key--value-)|指定した設定をブックに設定または追加します。|
||[getCount()](/javascript/api/excel/excel.settingcollection#getcount--)|コレクションに含まれる設定の数を取得します。|
||[getItem(key: string)](/javascript/api/excel/excel.settingcollection#getitem-key-)|キーに基づいて設定エントリを取得します。|
||[getItemOrNullObject(key: string)](/javascript/api/excel/excel.settingcollection#getitemornullobject-key-)|キーに基づいて設定エントリを取得します。|
||[items](/javascript/api/excel/excel.settingcollection#items)|このコレクション内に読み込まれた子アイテムを取得します。|
||[onSettingsChanged](/javascript/api/excel/excel.settingcollection#onsettingschanged)|ドキュメント内の設定が変更されるときに発生します。|
|[SettingsChangedEventArgs](/javascript/api/excel/excel.settingschangedeventargs)|[settings](/javascript/api/excel/excel.settingschangedeventargs#settings)|SettingsChanged イベントが発生したバインドを表す Setting オブジェクトを取得します。|
|[TableCollection](/javascript/api/excel/excel.tablecollection)|[getCount()](/javascript/api/excel/excel.tablecollection#getcount--)|コレクションに含まれるテーブルの数を取得します。|
||[getItemOrNullObject(key: string)](/javascript/api/excel/excel.tablecollection#getitemornullobject-key-)|名前または ID を使用してテーブルを取得します。|
|[TableColumnCollection](/javascript/api/excel/excel.tablecolumncollection)|[getCount()](/javascript/api/excel/excel.tablecolumncollection#getcount--)|表の列数を取得します。|
||[getItemOrNullObject (key: number \| 文字列)](/javascript/api/excel/excel.tablecolumncollection#getitemornullobject-key-)|名前または ID を使用して列オブジェクトを取得します。|
|[TableRowCollection](/javascript/api/excel/excel.tablerowcollection)|[getCount()](/javascript/api/excel/excel.tablerowcollection#getcount--)|表の行数を取得します。|
|[Workbook](/javascript/api/excel/excel.workbook)|[settings](/javascript/api/excel/excel.workbook#settings)|ブックに関連付けられている Setting のコレクションを表します。|
|[Worksheet](/javascript/api/excel/excel.worksheet)|[getUsedRangeOrNullObject (パラメーターの設定のみ?: boolean)](/javascript/api/excel/excel.worksheet#getusedrangeornullobject-valuesonly-)|使用範囲とは、値または書式設定が割り当たっているすべてのセルを包含する最小の範囲です。|
||[姓名](/javascript/api/excel/excel.worksheet#names)|現在のワークシートにスコープされている名前のコレクション。|
|[WorksheetCollection](/javascript/api/excel/excel.worksheetcollection)|[getCount (visibleOnly?: boolean)](/javascript/api/excel/excel.worksheetcollection#getcount-visibleonly-)|コレクションに含まれるワークシートの数を取得します。|
||[getItemOrNullObject(key: string)](/javascript/api/excel/excel.worksheetcollection#getitemornullobject-key-)|名前または ID を使用して、ワークシート オブジェクトを取得します。|
