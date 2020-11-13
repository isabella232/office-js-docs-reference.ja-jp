| <span data-ttu-id="06f23-101">クラス</span><span class="sxs-lookup"><span data-stu-id="06f23-101">Class</span></span> | <span data-ttu-id="06f23-102">フィールド</span><span class="sxs-lookup"><span data-stu-id="06f23-102">Fields</span></span> | <span data-ttu-id="06f23-103">説明</span><span class="sxs-lookup"><span data-stu-id="06f23-103">Description</span></span> |
|:---|:---|:---|
|[<span data-ttu-id="06f23-104">LinkedDataType</span><span class="sxs-lookup"><span data-stu-id="06f23-104">LinkedDataType</span></span>](/javascript/api/excel/excel.linkeddatatype)|[<span data-ttu-id="06f23-105">プロバイダー</span><span class="sxs-lookup"><span data-stu-id="06f23-105">dataProvider</span></span>](/javascript/api/excel/excel.linkeddatatype#dataprovider)|<span data-ttu-id="06f23-106">リンクされたデータ型のデータプロバイダーの名前を指定します。</span><span class="sxs-lookup"><span data-stu-id="06f23-106">The name of the data provider for the linked data type.</span></span>|
||[<span data-ttu-id="06f23-107">lastRefreshed</span><span class="sxs-lookup"><span data-stu-id="06f23-107">lastRefreshed</span></span>](/javascript/api/excel/excel.linkeddatatype#lastrefreshed)|<span data-ttu-id="06f23-108">リンクされたデータ型が最後に更新されたときに、ブックが開かれてからのローカルタイムゾーンの日付と時刻。</span><span class="sxs-lookup"><span data-stu-id="06f23-108">The local time-zone date and time since the workbook was opened when the linked data type was last refreshed.</span></span>|
||[<span data-ttu-id="06f23-109">name</span><span class="sxs-lookup"><span data-stu-id="06f23-109">name</span></span>](/javascript/api/excel/excel.linkeddatatype#name)|<span data-ttu-id="06f23-110">リンクされたデータ型の名前を指定します。</span><span class="sxs-lookup"><span data-stu-id="06f23-110">The name of the linked data type.</span></span>|
||[<span data-ttu-id="06f23-111">periodicRefreshInterval</span><span class="sxs-lookup"><span data-stu-id="06f23-111">periodicRefreshInterval</span></span>](/javascript/api/excel/excel.linkeddatatype#periodicrefreshinterval)|<span data-ttu-id="06f23-112">リンクされたデータ型が `refreshMode` "定期的" に設定されている場合に更新される頻度 (秒単位)。</span><span class="sxs-lookup"><span data-stu-id="06f23-112">The frequency, in seconds, at which the linked data type is refreshed if `refreshMode` is set to "Periodic".</span></span>|
||[<span data-ttu-id="06f23-113">示し</span><span class="sxs-lookup"><span data-stu-id="06f23-113">refreshMode</span></span>](/javascript/api/excel/excel.linkeddatatype#refreshmode)|<span data-ttu-id="06f23-114">リンクされたデータ型のデータを取得するメカニズムを指定します。</span><span class="sxs-lookup"><span data-stu-id="06f23-114">The mechanism by which the data for the linked data type is retrieved.</span></span>|
||[<span data-ttu-id="06f23-115">serviceId</span><span class="sxs-lookup"><span data-stu-id="06f23-115">serviceId</span></span>](/javascript/api/excel/excel.linkeddatatype#serviceid)|<span data-ttu-id="06f23-116">リンクされたデータ型の一意の id。</span><span class="sxs-lookup"><span data-stu-id="06f23-116">The unique id of the linked data type.</span></span>|
||[<span data-ttu-id="06f23-117">supportedRefreshModes</span><span class="sxs-lookup"><span data-stu-id="06f23-117">supportedRefreshModes</span></span>](/javascript/api/excel/excel.linkeddatatype#supportedrefreshmodes)|<span data-ttu-id="06f23-118">リンクされたデータ型によってサポートされるすべての更新モードを含む配列を返します。</span><span class="sxs-lookup"><span data-stu-id="06f23-118">Returns an array with all the refresh modes supported by the linked data type.</span></span>|
||[<span data-ttu-id="06f23-119">requestRefresh ()</span><span class="sxs-lookup"><span data-stu-id="06f23-119">requestRefresh()</span></span>](/javascript/api/excel/excel.linkeddatatype#requestrefresh--)|<span data-ttu-id="06f23-120">リンクされたデータ型を更新する要求を行います。</span><span class="sxs-lookup"><span data-stu-id="06f23-120">Makes a request to refresh the linked data type.</span></span>|
||[<span data-ttu-id="06f23-121">requestSetRefreshMode (refreshMode: LinkedDataTypeRefreshMode)</span><span class="sxs-lookup"><span data-stu-id="06f23-121">requestSetRefreshMode(refreshMode: Excel.LinkedDataTypeRefreshMode)</span></span>](/javascript/api/excel/excel.linkeddatatype#requestsetrefreshmode-refreshmode-)|<span data-ttu-id="06f23-122">このリンクされたデータ型の更新モードを変更する要求を行います。</span><span class="sxs-lookup"><span data-stu-id="06f23-122">Makes a request to change the refresh mode for this linked data type.</span></span>|
|[<span data-ttu-id="06f23-123">LinkedDataTypeAddedEventArgs</span><span class="sxs-lookup"><span data-stu-id="06f23-123">LinkedDataTypeAddedEventArgs</span></span>](/javascript/api/excel/excel.linkeddatatypeaddedeventargs)|[<span data-ttu-id="06f23-124">serviceId</span><span class="sxs-lookup"><span data-stu-id="06f23-124">serviceId</span></span>](/javascript/api/excel/excel.linkeddatatypeaddedeventargs#serviceid)|<span data-ttu-id="06f23-125">新しいリンクされたデータ型の一意の id。</span><span class="sxs-lookup"><span data-stu-id="06f23-125">The unique id of the new linked data type.</span></span>|
||[<span data-ttu-id="06f23-126">source</span><span class="sxs-lookup"><span data-stu-id="06f23-126">source</span></span>](/javascript/api/excel/excel.linkeddatatypeaddedeventargs#source)|<span data-ttu-id="06f23-127">イベントのソースを取得します。</span><span class="sxs-lookup"><span data-stu-id="06f23-127">Gets the source of the event.</span></span>|
||[<span data-ttu-id="06f23-128">type</span><span class="sxs-lookup"><span data-stu-id="06f23-128">type</span></span>](/javascript/api/excel/excel.linkeddatatypeaddedeventargs#type)|<span data-ttu-id="06f23-129">イベントの種類を取得します。</span><span class="sxs-lookup"><span data-stu-id="06f23-129">Gets the type of the event.</span></span>|
|[<span data-ttu-id="06f23-130">LinkedDataTypeCollection</span><span class="sxs-lookup"><span data-stu-id="06f23-130">LinkedDataTypeCollection</span></span>](/javascript/api/excel/excel.linkeddatatypecollection)|[<span data-ttu-id="06f23-131">getCount()</span><span class="sxs-lookup"><span data-stu-id="06f23-131">getCount()</span></span>](/javascript/api/excel/excel.linkeddatatypecollection#getcount--)|<span data-ttu-id="06f23-132">コレクション内のリンクされたデータ型の数を取得します。</span><span class="sxs-lookup"><span data-stu-id="06f23-132">Gets the number of linked data types in the collection.</span></span>|
||[<span data-ttu-id="06f23-133">getItem (key: number)</span><span class="sxs-lookup"><span data-stu-id="06f23-133">getItem(key: number)</span></span>](/javascript/api/excel/excel.linkeddatatypecollection#getitem-key-)|<span data-ttu-id="06f23-134">リンクされたデータ型をサービス id で取得します。</span><span class="sxs-lookup"><span data-stu-id="06f23-134">Gets a linked data type by service id.</span></span>|
||[<span data-ttu-id="06f23-135">getItemAt(index: number)</span><span class="sxs-lookup"><span data-stu-id="06f23-135">getItemAt(index: number)</span></span>](/javascript/api/excel/excel.linkeddatatypecollection#getitemat-index-)|<span data-ttu-id="06f23-136">コレクション内のインデックスによって、リンクされたデータ型を取得します。</span><span class="sxs-lookup"><span data-stu-id="06f23-136">Gets a linked data type by its index in the collection.</span></span>|
||[<span data-ttu-id="06f23-137">getItemOrNullObject (key: number)</span><span class="sxs-lookup"><span data-stu-id="06f23-137">getItemOrNullObject(key: number)</span></span>](/javascript/api/excel/excel.linkeddatatypecollection#getitemornullobject-key-)|<span data-ttu-id="06f23-138">ID でリンクされたデータ型を取得します。</span><span class="sxs-lookup"><span data-stu-id="06f23-138">Gets a linked data type by ID.</span></span>|
||[<span data-ttu-id="06f23-139">items</span><span class="sxs-lookup"><span data-stu-id="06f23-139">items</span></span>](/javascript/api/excel/excel.linkeddatatypecollection#items)|<span data-ttu-id="06f23-140">このコレクション内に読み込まれた子アイテムを取得します。</span><span class="sxs-lookup"><span data-stu-id="06f23-140">Gets the loaded child items in this collection.</span></span>|
||[<span data-ttu-id="06f23-141">requestRefreshAll()</span><span class="sxs-lookup"><span data-stu-id="06f23-141">requestRefreshAll()</span></span>](/javascript/api/excel/excel.linkeddatatypecollection#requestrefreshall--)|<span data-ttu-id="06f23-142">コレクション内のすべてのリンクされたデータ型を更新する要求を行います。</span><span class="sxs-lookup"><span data-stu-id="06f23-142">Makes a request to refresh all the linked data types in the collection.</span></span>|
|[<span data-ttu-id="06f23-143">NamedSheetView</span><span class="sxs-lookup"><span data-stu-id="06f23-143">NamedSheetView</span></span>](/javascript/api/excel/excel.namedsheetview)|[<span data-ttu-id="06f23-144">activate()</span><span class="sxs-lookup"><span data-stu-id="06f23-144">activate()</span></span>](/javascript/api/excel/excel.namedsheetview#activate--)|<span data-ttu-id="06f23-145">このシートビューをアクティブにします。</span><span class="sxs-lookup"><span data-stu-id="06f23-145">Activates this sheet view.</span></span>|
||[<span data-ttu-id="06f23-146">delete()</span><span class="sxs-lookup"><span data-stu-id="06f23-146">delete()</span></span>](/javascript/api/excel/excel.namedsheetview#delete--)|<span data-ttu-id="06f23-147">ワークシートからシートビューを削除します。</span><span class="sxs-lookup"><span data-stu-id="06f23-147">Removes the sheet view from the worksheet.</span></span>|
||[<span data-ttu-id="06f23-148">重複 (名前?: string)</span><span class="sxs-lookup"><span data-stu-id="06f23-148">duplicate(name?: string)</span></span>](/javascript/api/excel/excel.namedsheetview#duplicate-name-)|<span data-ttu-id="06f23-149">このシートビューのコピーを作成します。</span><span class="sxs-lookup"><span data-stu-id="06f23-149">Creates a copy of this sheet view.</span></span>|
||[<span data-ttu-id="06f23-150">name</span><span class="sxs-lookup"><span data-stu-id="06f23-150">name</span></span>](/javascript/api/excel/excel.namedsheetview#name)|<span data-ttu-id="06f23-151">シートビューの名前を取得または設定します。</span><span class="sxs-lookup"><span data-stu-id="06f23-151">Gets or sets the name of the sheet view.</span></span>|
|[<span data-ttu-id="06f23-152">NamedSheetViewCollection</span><span class="sxs-lookup"><span data-stu-id="06f23-152">NamedSheetViewCollection</span></span>](/javascript/api/excel/excel.namedsheetviewcollection)|[<span data-ttu-id="06f23-153">add(name: string)</span><span class="sxs-lookup"><span data-stu-id="06f23-153">add(name: string)</span></span>](/javascript/api/excel/excel.namedsheetviewcollection#add-name-)|<span data-ttu-id="06f23-154">指定した名前の新しいシートビューを作成します。</span><span class="sxs-lookup"><span data-stu-id="06f23-154">Creates a new sheet view with the given name.</span></span>|
||[<span data-ttu-id="06f23-155">enterTemporary ()</span><span class="sxs-lookup"><span data-stu-id="06f23-155">enterTemporary()</span></span>](/javascript/api/excel/excel.namedsheetviewcollection#entertemporary--)|<span data-ttu-id="06f23-156">新しい一時シートビューを作成してアクティブにします。</span><span class="sxs-lookup"><span data-stu-id="06f23-156">Creates and activates a new temporary sheet view.</span></span>|
||[<span data-ttu-id="06f23-157">exit ()</span><span class="sxs-lookup"><span data-stu-id="06f23-157">exit()</span></span>](/javascript/api/excel/excel.namedsheetviewcollection#exit--)|<span data-ttu-id="06f23-158">現在アクティブなシートビューを終了します。</span><span class="sxs-lookup"><span data-stu-id="06f23-158">Exits the currently active sheet view.</span></span>|
||[<span data-ttu-id="06f23-159">getActive ()</span><span class="sxs-lookup"><span data-stu-id="06f23-159">getActive()</span></span>](/javascript/api/excel/excel.namedsheetviewcollection#getactive--)|<span data-ttu-id="06f23-160">ワークシートの現在アクティブなシートビューを取得します。</span><span class="sxs-lookup"><span data-stu-id="06f23-160">Gets the worksheet's currently active sheet view.</span></span>|
||[<span data-ttu-id="06f23-161">getCount()</span><span class="sxs-lookup"><span data-stu-id="06f23-161">getCount()</span></span>](/javascript/api/excel/excel.namedsheetviewcollection#getcount--)|<span data-ttu-id="06f23-162">このワークシートのシートビューの数を取得します。</span><span class="sxs-lookup"><span data-stu-id="06f23-162">Gets the number of sheet views in this worksheet.</span></span>|
||[<span data-ttu-id="06f23-163">getItem(key: string)</span><span class="sxs-lookup"><span data-stu-id="06f23-163">getItem(key: string)</span></span>](/javascript/api/excel/excel.namedsheetviewcollection#getitem-key-)|<span data-ttu-id="06f23-164">名前を使用してシートビューを取得します。</span><span class="sxs-lookup"><span data-stu-id="06f23-164">Gets a sheet view using its name.</span></span>|
||[<span data-ttu-id="06f23-165">getItemAt(index: number)</span><span class="sxs-lookup"><span data-stu-id="06f23-165">getItemAt(index: number)</span></span>](/javascript/api/excel/excel.namedsheetviewcollection#getitemat-index-)|<span data-ttu-id="06f23-166">コレクション内のインデックスによってシートビューを取得します。</span><span class="sxs-lookup"><span data-stu-id="06f23-166">Gets a sheet view by its index in the collection.</span></span>|
||[<span data-ttu-id="06f23-167">items</span><span class="sxs-lookup"><span data-stu-id="06f23-167">items</span></span>](/javascript/api/excel/excel.namedsheetviewcollection#items)|<span data-ttu-id="06f23-168">このコレクション内に読み込まれた子アイテムを取得します。</span><span class="sxs-lookup"><span data-stu-id="06f23-168">Gets the loaded child items in this collection.</span></span>|
|[<span data-ttu-id="06f23-169">PivotLayout</span><span class="sxs-lookup"><span data-stu-id="06f23-169">PivotLayout</span></span>](/javascript/api/excel/excel.pivotlayout)|[<span data-ttu-id="06f23-170">altTextDescription</span><span class="sxs-lookup"><span data-stu-id="06f23-170">altTextDescription</span></span>](/javascript/api/excel/excel.pivotlayout#alttextdescription)|<span data-ttu-id="06f23-171">ピボットテーブルの代替テキストの説明。</span><span class="sxs-lookup"><span data-stu-id="06f23-171">The alt text description of the PivotTable.</span></span>|
||[<span data-ttu-id="06f23-172">altTextTitle</span><span class="sxs-lookup"><span data-stu-id="06f23-172">altTextTitle</span></span>](/javascript/api/excel/excel.pivotlayout#alttexttitle)|<span data-ttu-id="06f23-173">ピボットテーブルの代替テキストタイトル。</span><span class="sxs-lookup"><span data-stu-id="06f23-173">The alt text title of the PivotTable.</span></span>|
||[<span data-ttu-id="06f23-174">各アイテムを表示する (display: boolean)</span><span class="sxs-lookup"><span data-stu-id="06f23-174">displayBlankLineAfterEachItem(display: boolean)</span></span>](/javascript/api/excel/excel.pivotlayout#displayblanklineaftereachitem-display-)|<span data-ttu-id="06f23-175">各アイテムの後に空白行を表示するかどうかを設定します。</span><span class="sxs-lookup"><span data-stu-id="06f23-175">Sets whether or not to display a blank line after each item.</span></span>|
||[<span data-ttu-id="06f23-176">emptyCellText</span><span class="sxs-lookup"><span data-stu-id="06f23-176">emptyCellText</span></span>](/javascript/api/excel/excel.pivotlayout#emptycelltext)|<span data-ttu-id="06f23-177">ピボットテーブル内の空のセルに自動的に入力されるテキスト `fillEmptyCells == true` 。</span><span class="sxs-lookup"><span data-stu-id="06f23-177">The text that is automatically filled into any empty cell in the PivotTable if `fillEmptyCells == true`.</span></span>|
||[<span data-ttu-id="06f23-178">fillEmptyCells</span><span class="sxs-lookup"><span data-stu-id="06f23-178">fillEmptyCells</span></span>](/javascript/api/excel/excel.pivotlayout#fillemptycells)|<span data-ttu-id="06f23-179">ピボットテーブルの空のセルにを設定するかどうかを指定し `emptyCellText` ます。</span><span class="sxs-lookup"><span data-stu-id="06f23-179">Specifies whether empty cells in the PivotTable should be populated with the `emptyCellText`.</span></span>|
||[<span data-ttu-id="06f23-180">getCell(dataHierarchy: DataPivotHierarchy \| string, rowItems: Array<PivotItem \| string>, columnItems: Array<PivotItem \| string>)</span><span class="sxs-lookup"><span data-stu-id="06f23-180">getCell(dataHierarchy: DataPivotHierarchy \| string, rowItems: Array<PivotItem \| string>, columnItems: Array<PivotItem \| string>)</span></span>](/javascript/api/excel/excel.pivotlayout#getcell-datahierarchy--rowitems--columnitems-)|<span data-ttu-id="06f23-181">データ階層と、それぞれの階層の行および列の項目に基づいて、ピボットテーブル内の一意のセルを取得します。 </span><span class="sxs-lookup"><span data-stu-id="06f23-181">Gets a unique cell in the PivotTable based on a data hierarchy and the row and column items of their respective hierarchies.</span></span>|
||[<span data-ttu-id="06f23-182">pivotStyle</span><span class="sxs-lookup"><span data-stu-id="06f23-182">pivotStyle</span></span>](/javascript/api/excel/excel.pivotlayout#pivotstyle)|<span data-ttu-id="06f23-183">ピボットテーブルに適用されるスタイルです。</span><span class="sxs-lookup"><span data-stu-id="06f23-183">The style applied to the PivotTable.</span></span>|
||[<span data-ttu-id="06f23-184">repeatAllItemLabels (repeatLabels: boolean)</span><span class="sxs-lookup"><span data-stu-id="06f23-184">repeatAllItemLabels(repeatLabels: boolean)</span></span>](/javascript/api/excel/excel.pivotlayout#repeatallitemlabels-repeatlabels-)|<span data-ttu-id="06f23-185">ピボットテーブルのすべてのフィールドで [すべてのアイテムのラベルを繰り返す] 設定を設定します。</span><span class="sxs-lookup"><span data-stu-id="06f23-185">Sets the "repeat all item labels" setting across all fields in the PivotTable.</span></span>|
||[<span data-ttu-id="06f23-186">setStyle (style: string \| PivotTableStyle \| BuiltInPivotTableStyle)</span><span class="sxs-lookup"><span data-stu-id="06f23-186">setStyle(style: string \| PivotTableStyle \| BuiltInPivotTableStyle)</span></span>](/javascript/api/excel/excel.pivotlayout#setstyle-style-)|<span data-ttu-id="06f23-187">ピボットテーブルに適用されるスタイルを設定します。</span><span class="sxs-lookup"><span data-stu-id="06f23-187">Sets the style applied to the PivotTable.</span></span>|
||[<span data-ttu-id="06f23-188">showFieldHeaders</span><span class="sxs-lookup"><span data-stu-id="06f23-188">showFieldHeaders</span></span>](/javascript/api/excel/excel.pivotlayout#showfieldheaders)|<span data-ttu-id="06f23-189">ピボットテーブルにフィールドヘッダーを表示するかどうかを指定します (フィールドのタイトルとフィルターのドロップダウン)。</span><span class="sxs-lookup"><span data-stu-id="06f23-189">Specifies whether the PivotTable displays field headers (field captions and filter drop-downs).</span></span>|
|[<span data-ttu-id="06f23-190">PivotTable</span><span class="sxs-lookup"><span data-stu-id="06f23-190">PivotTable</span></span>](/javascript/api/excel/excel.pivottable)|[<span data-ttu-id="06f23-191">refreshOnOpen</span><span class="sxs-lookup"><span data-stu-id="06f23-191">refreshOnOpen</span></span>](/javascript/api/excel/excel.pivottable#refreshonopen)|<span data-ttu-id="06f23-192">ブックを開くときにピボットテーブルを更新するかどうかを指定します。</span><span class="sxs-lookup"><span data-stu-id="06f23-192">Specifies whether the PivotTable refreshes when the workbook opens.</span></span>|
|[<span data-ttu-id="06f23-193">Range</span><span class="sxs-lookup"><span data-stu-id="06f23-193">Range</span></span>](/javascript/api/excel/excel.range)|[<span data-ttu-id="06f23-194">getPrecedents 元 ()</span><span class="sxs-lookup"><span data-stu-id="06f23-194">getPrecedents()</span></span>](/javascript/api/excel/excel.range#getprecedents--)|<span data-ttu-id="06f23-195">`WorkbookRangeAreas`同じワークシートまたは複数のワークシート内のセルのすべての参照元を含む範囲を表すオブジェクト型 (object) の値を取得します。</span><span class="sxs-lookup"><span data-stu-id="06f23-195">Returns a `WorkbookRangeAreas` object that represents the range containing all the precedents of a cell in same worksheet or in multiple worksheets.</span></span>|
|[<span data-ttu-id="06f23-196">RefreshModeChangedEventArgs</span><span class="sxs-lookup"><span data-stu-id="06f23-196">RefreshModeChangedEventArgs</span></span>](/javascript/api/excel/excel.refreshmodechangedeventargs)|[<span data-ttu-id="06f23-197">示し</span><span class="sxs-lookup"><span data-stu-id="06f23-197">refreshMode</span></span>](/javascript/api/excel/excel.refreshmodechangedeventargs#refreshmode)|<span data-ttu-id="06f23-198">リンクされたデータ型の更新モード。</span><span class="sxs-lookup"><span data-stu-id="06f23-198">The linked data type refresh mode.</span></span>|
||[<span data-ttu-id="06f23-199">serviceId</span><span class="sxs-lookup"><span data-stu-id="06f23-199">serviceId</span></span>](/javascript/api/excel/excel.refreshmodechangedeventargs#serviceid)|<span data-ttu-id="06f23-200">更新モードが変更されたオブジェクトの一意の id です。</span><span class="sxs-lookup"><span data-stu-id="06f23-200">The unique id of the object whose refresh mode was changed.</span></span>|
||[<span data-ttu-id="06f23-201">source</span><span class="sxs-lookup"><span data-stu-id="06f23-201">source</span></span>](/javascript/api/excel/excel.refreshmodechangedeventargs#source)|<span data-ttu-id="06f23-202">イベントのソースを取得します。</span><span class="sxs-lookup"><span data-stu-id="06f23-202">Gets the source of the event.</span></span>|
||[<span data-ttu-id="06f23-203">type</span><span class="sxs-lookup"><span data-stu-id="06f23-203">type</span></span>](/javascript/api/excel/excel.refreshmodechangedeventargs#type)|<span data-ttu-id="06f23-204">イベントの種類を取得します。</span><span class="sxs-lookup"><span data-stu-id="06f23-204">Gets the type of the event.</span></span>|
|[<span data-ttu-id="06f23-205">RefreshRequestCompletedEventArgs</span><span class="sxs-lookup"><span data-stu-id="06f23-205">RefreshRequestCompletedEventArgs</span></span>](/javascript/api/excel/excel.refreshrequestcompletedeventargs)|[<span data-ttu-id="06f23-206">更新</span><span class="sxs-lookup"><span data-stu-id="06f23-206">refreshed</span></span>](/javascript/api/excel/excel.refreshrequestcompletedeventargs#refreshed)|<span data-ttu-id="06f23-207">更新要求が正常に終了したかどうかを示します。</span><span class="sxs-lookup"><span data-stu-id="06f23-207">Indicates if the request to refresh was successful.</span></span>|
||[<span data-ttu-id="06f23-208">serviceId</span><span class="sxs-lookup"><span data-stu-id="06f23-208">serviceId</span></span>](/javascript/api/excel/excel.refreshrequestcompletedeventargs#serviceid)|<span data-ttu-id="06f23-209">更新要求が完了したオブジェクトの一意の id。</span><span class="sxs-lookup"><span data-stu-id="06f23-209">The unique id of the object whose refresh request was completed.</span></span>|
||[<span data-ttu-id="06f23-210">source</span><span class="sxs-lookup"><span data-stu-id="06f23-210">source</span></span>](/javascript/api/excel/excel.refreshrequestcompletedeventargs#source)|<span data-ttu-id="06f23-211">イベントのソースを取得します。</span><span class="sxs-lookup"><span data-stu-id="06f23-211">Gets the source of the event.</span></span>|
||[<span data-ttu-id="06f23-212">type</span><span class="sxs-lookup"><span data-stu-id="06f23-212">type</span></span>](/javascript/api/excel/excel.refreshrequestcompletedeventargs#type)|<span data-ttu-id="06f23-213">イベントの種類を取得します。</span><span class="sxs-lookup"><span data-stu-id="06f23-213">Gets the type of the event.</span></span>|
||[<span data-ttu-id="06f23-214">注意</span><span class="sxs-lookup"><span data-stu-id="06f23-214">warnings</span></span>](/javascript/api/excel/excel.refreshrequestcompletedeventargs#warnings)|<span data-ttu-id="06f23-215">更新要求によって生成された警告を含む配列。</span><span class="sxs-lookup"><span data-stu-id="06f23-215">An array that contains any warnings generated from the refresh request.</span></span>|
|[<span data-ttu-id="06f23-216">ShapeCollection</span><span class="sxs-lookup"><span data-stu-id="06f23-216">ShapeCollection</span></span>](/javascript/api/excel/excel.shapecollection)|[<span data-ttu-id="06f23-217">addSvg(xml: string)</span><span class="sxs-lookup"><span data-stu-id="06f23-217">addSvg(xml: string)</span></span>](/javascript/api/excel/excel.shapecollection#addsvg-xml-)|<span data-ttu-id="06f23-218">XML 文字列からスケーラブルなベクター グラフィックス (SVG) を作成し、それをワークシートに追加します。</span><span class="sxs-lookup"><span data-stu-id="06f23-218">Creates a scalable vector graphic (SVG) from an XML string and adds it to the worksheet.</span></span>|
|[<span data-ttu-id="06f23-219">Slicer</span><span class="sxs-lookup"><span data-stu-id="06f23-219">Slicer</span></span>](/javascript/api/excel/excel.slicer)|[<span data-ttu-id="06f23-220">nameInFormula</span><span class="sxs-lookup"><span data-stu-id="06f23-220">nameInFormula</span></span>](/javascript/api/excel/excel.slicer#nameinformula)|<span data-ttu-id="06f23-221">数式で使用するスライサーの名前を表します。</span><span class="sxs-lookup"><span data-stu-id="06f23-221">Represents the slicer name used in the formula.</span></span>|
||[<span data-ttu-id="06f23-222">slicerStyle</span><span class="sxs-lookup"><span data-stu-id="06f23-222">slicerStyle</span></span>](/javascript/api/excel/excel.slicer#slicerstyle)|<span data-ttu-id="06f23-223">スライサーに適用されるスタイルです。</span><span class="sxs-lookup"><span data-stu-id="06f23-223">The style applied to the Slicer.</span></span>|
||[<span data-ttu-id="06f23-224">setStyle (style: string \| SlicerStyle \| BuiltInSlicerStyle)</span><span class="sxs-lookup"><span data-stu-id="06f23-224">setStyle(style: string \| SlicerStyle \| BuiltInSlicerStyle)</span></span>](/javascript/api/excel/excel.slicer#setstyle-style-)|<span data-ttu-id="06f23-225">スライサーに適用されるスタイルを設定します。</span><span class="sxs-lookup"><span data-stu-id="06f23-225">Sets the style applied to the slicer.</span></span>|
|[<span data-ttu-id="06f23-226">Table</span><span class="sxs-lookup"><span data-stu-id="06f23-226">Table</span></span>](/javascript/api/excel/excel.table)|[<span data-ttu-id="06f23-227">clearStyle()</span><span class="sxs-lookup"><span data-stu-id="06f23-227">clearStyle()</span></span>](/javascript/api/excel/excel.table#clearstyle--)|<span data-ttu-id="06f23-228">既定のテーブル スタイルを使用するようにテーブルを変更します。</span><span class="sxs-lookup"><span data-stu-id="06f23-228">Changes the table to use the default table style.</span></span>|
||[<span data-ttu-id="06f23-229">onFiltered</span><span class="sxs-lookup"><span data-stu-id="06f23-229">onFiltered</span></span>](/javascript/api/excel/excel.table#onfiltered)|<span data-ttu-id="06f23-230">フィルターが特定のテーブルに適用されたときに発生します。</span><span class="sxs-lookup"><span data-stu-id="06f23-230">Occurs when filter is applied on a specific table.</span></span>|
||[<span data-ttu-id="06f23-231">tableStyle</span><span class="sxs-lookup"><span data-stu-id="06f23-231">tableStyle</span></span>](/javascript/api/excel/excel.table#tablestyle)|<span data-ttu-id="06f23-232">表に適用されるスタイルです。</span><span class="sxs-lookup"><span data-stu-id="06f23-232">The style applied to the Table.</span></span>|
||[<span data-ttu-id="06f23-233">setStyle (style: string \| TableStyle \| BuiltInTableStyle)</span><span class="sxs-lookup"><span data-stu-id="06f23-233">setStyle(style: string \| TableStyle \| BuiltInTableStyle)</span></span>](/javascript/api/excel/excel.table#setstyle-style-)|<span data-ttu-id="06f23-234">表に適用するスタイルを設定します。</span><span class="sxs-lookup"><span data-stu-id="06f23-234">Sets the style applied to the table.</span></span>|
|[<span data-ttu-id="06f23-235">TableCollection</span><span class="sxs-lookup"><span data-stu-id="06f23-235">TableCollection</span></span>](/javascript/api/excel/excel.tablecollection)|[<span data-ttu-id="06f23-236">onFiltered</span><span class="sxs-lookup"><span data-stu-id="06f23-236">onFiltered</span></span>](/javascript/api/excel/excel.tablecollection#onfiltered)|<span data-ttu-id="06f23-237">ブックまたはワークシートのテーブルにフィルターが適用されたときに発生します。</span><span class="sxs-lookup"><span data-stu-id="06f23-237">Occurs when filter is applied on any table in a workbook, or a worksheet.</span></span>|
|[<span data-ttu-id="06f23-238">TableFilteredEventArgs</span><span class="sxs-lookup"><span data-stu-id="06f23-238">TableFilteredEventArgs</span></span>](/javascript/api/excel/excel.tablefilteredeventargs)|[<span data-ttu-id="06f23-239">tableId</span><span class="sxs-lookup"><span data-stu-id="06f23-239">tableId</span></span>](/javascript/api/excel/excel.tablefilteredeventargs#tableid)|<span data-ttu-id="06f23-240">フィルターが適用されているテーブルの id を取得します。</span><span class="sxs-lookup"><span data-stu-id="06f23-240">Gets the id of the table in which the filter is applied.</span></span>|
||[<span data-ttu-id="06f23-241">type</span><span class="sxs-lookup"><span data-stu-id="06f23-241">type</span></span>](/javascript/api/excel/excel.tablefilteredeventargs#type)|<span data-ttu-id="06f23-242">イベントの種類を取得します。</span><span class="sxs-lookup"><span data-stu-id="06f23-242">Gets the type of the event.</span></span>|
||[<span data-ttu-id="06f23-243">worksheetId</span><span class="sxs-lookup"><span data-stu-id="06f23-243">worksheetId</span></span>](/javascript/api/excel/excel.tablefilteredeventargs#worksheetid)|<span data-ttu-id="06f23-244">テーブルを含むワークシートの id を取得します。</span><span class="sxs-lookup"><span data-stu-id="06f23-244">Gets the id of the worksheet which contains the table.</span></span>|
|[<span data-ttu-id="06f23-245">Workbook</span><span class="sxs-lookup"><span data-stu-id="06f23-245">Workbook</span></span>](/javascript/api/excel/excel.workbook)|[<span data-ttu-id="06f23-246">linkedDataTypes 型</span><span class="sxs-lookup"><span data-stu-id="06f23-246">linkedDataTypes</span></span>](/javascript/api/excel/excel.workbook#linkeddatatypes)|<span data-ttu-id="06f23-247">ブックの一部である、リンクされたデータ型のコレクションを返します。</span><span class="sxs-lookup"><span data-stu-id="06f23-247">Returns a collection of linked data types that are part of the workbook.</span></span>|
||[<span data-ttu-id="06f23-248">showPivotFieldList</span><span class="sxs-lookup"><span data-stu-id="06f23-248">showPivotFieldList</span></span>](/javascript/api/excel/excel.workbook#showpivotfieldlist)|<span data-ttu-id="06f23-249">ピボットテーブルのフィールドリストウィンドウをブックレベルで表示するかどうかを指定します。</span><span class="sxs-lookup"><span data-stu-id="06f23-249">Specifies whether the PivotTable's field list pane is shown at the workbook level.</span></span>|
||[<span data-ttu-id="06f23-250">use1904DateSystem</span><span class="sxs-lookup"><span data-stu-id="06f23-250">use1904DateSystem</span></span>](/javascript/api/excel/excel.workbook#use1904datesystem)|<span data-ttu-id="06f23-251">ブックの日付を 1904 年から計算する場合、true となります。</span><span class="sxs-lookup"><span data-stu-id="06f23-251">True if the workbook uses the 1904 date system.</span></span>|
|[<span data-ttu-id="06f23-252">Worksheet</span><span class="sxs-lookup"><span data-stu-id="06f23-252">Worksheet</span></span>](/javascript/api/excel/excel.worksheet)|[<span data-ttu-id="06f23-253">namedSheetViews</span><span class="sxs-lookup"><span data-stu-id="06f23-253">namedSheetViews</span></span>](/javascript/api/excel/excel.worksheet#namedsheetviews)|<span data-ttu-id="06f23-254">ワークシートにあるシートビューのコレクションを返します。</span><span class="sxs-lookup"><span data-stu-id="06f23-254">Returns a collection of sheet views that are present in the worksheet.</span></span>|
||[<span data-ttu-id="06f23-255">onFiltered</span><span class="sxs-lookup"><span data-stu-id="06f23-255">onFiltered</span></span>](/javascript/api/excel/excel.worksheet#onfiltered)|<span data-ttu-id="06f23-256">フィルターが特定のワークシートに適用されたときに発生します。</span><span class="sxs-lookup"><span data-stu-id="06f23-256">Occurs when filter is applied on a specific worksheet.</span></span>|
|[<span data-ttu-id="06f23-257">WorksheetCollection</span><span class="sxs-lookup"><span data-stu-id="06f23-257">WorksheetCollection</span></span>](/javascript/api/excel/excel.worksheetcollection)|<span data-ttu-id="06f23-258">[addFromBase64(base64File: string, sheetNamesToInsert?: string[], positionType?: Excel.WorksheetPositionType, relativeTo?: Worksheet \| string)](/javascript/api/excel/excel.worksheetcollection#addfrombase64-base64file--sheetnamestoinsert--positiontype--relativeto-)</span><span class="sxs-lookup"><span data-stu-id="06f23-258">[addFromBase64(base64File: string, sheetNamesToInsert?: string[], positionType?: Excel.WorksheetPositionType, relativeTo?: Worksheet \| string)](/javascript/api/excel/excel.worksheetcollection#addfrombase64-base64file--sheetnamestoinsert--positiontype--relativeto-)</span></span>|<span data-ttu-id="06f23-259">あるブックの指定されたワークシートを現在のブックに挿入します。</span><span class="sxs-lookup"><span data-stu-id="06f23-259">Inserts the specified worksheets of a workbook into the current workbook.</span></span>|
||[<span data-ttu-id="06f23-260">onFiltered</span><span class="sxs-lookup"><span data-stu-id="06f23-260">onFiltered</span></span>](/javascript/api/excel/excel.worksheetcollection#onfiltered)|<span data-ttu-id="06f23-261">ブック内でワークシートのフィルターが適用されたときに発生します。</span><span class="sxs-lookup"><span data-stu-id="06f23-261">Occurs when any worksheet's filter is applied in the workbook.</span></span>|
|[<span data-ttu-id="06f23-262">WorksheetFilteredEventArgs</span><span class="sxs-lookup"><span data-stu-id="06f23-262">WorksheetFilteredEventArgs</span></span>](/javascript/api/excel/excel.worksheetfilteredeventargs)|[<span data-ttu-id="06f23-263">type</span><span class="sxs-lookup"><span data-stu-id="06f23-263">type</span></span>](/javascript/api/excel/excel.worksheetfilteredeventargs#type)|<span data-ttu-id="06f23-264">イベントの種類を取得します。</span><span class="sxs-lookup"><span data-stu-id="06f23-264">Gets the type of the event.</span></span>|
||[<span data-ttu-id="06f23-265">worksheetId</span><span class="sxs-lookup"><span data-stu-id="06f23-265">worksheetId</span></span>](/javascript/api/excel/excel.worksheetfilteredeventargs#worksheetid)|<span data-ttu-id="06f23-266">フィルターが適用されているワークシートの id を取得します。</span><span class="sxs-lookup"><span data-stu-id="06f23-266">Gets the id of the worksheet in which the filter is applied.</span></span>|