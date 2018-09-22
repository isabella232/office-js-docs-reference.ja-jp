 

# <a name="office"></a><span data-ttu-id="354a0-101">Office</span><span class="sxs-lookup"><span data-stu-id="354a0-101">Office</span></span>

<span data-ttu-id="354a0-p101">Office 名前空間は、すべての Office アプリケーションのアドインで使用される共有インターフェイスを提供します。この一覧は、Outlook のアドインで使うインターフェイスのみを記載しています。Office 名前空間の完全な一覧については、「[共有 API](/javascript/api/office)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="354a0-p101">The Office namespace provides shared interfaces that are used by add-ins in all of the Office apps. This listing documents only those interfaces that are used by Outlook add-ins. For a full listing of the Office namespace, see the [Shared API](/javascript/api/office).</span></span>

##### <a name="requirements"></a><span data-ttu-id="354a0-104">要件</span><span class="sxs-lookup"><span data-stu-id="354a0-104">Requirements</span></span>

|<span data-ttu-id="354a0-105">要件</span><span class="sxs-lookup"><span data-stu-id="354a0-105">Requirement</span></span>| <span data-ttu-id="354a0-106">値</span><span class="sxs-lookup"><span data-stu-id="354a0-106">Value</span></span>|
|---|---|
|[<span data-ttu-id="354a0-107">メールボックスの最小要件セットのバージョン</span><span class="sxs-lookup"><span data-stu-id="354a0-107">Minimum mailbox requirement set version</span></span>](/javascript/office/requirement-sets/outlook-api-requirement-sets)| <span data-ttu-id="354a0-108">1.0</span><span class="sxs-lookup"><span data-stu-id="354a0-108">1.0</span></span>|
|[<span data-ttu-id="354a0-109">適用可能な Outlook のモード</span><span class="sxs-lookup"><span data-stu-id="354a0-109">Applicable Outlook mode</span></span>](https://docs.microsoft.com/outlook/add-ins/#extension-points)| <span data-ttu-id="354a0-110">作成または読み取り</span><span class="sxs-lookup"><span data-stu-id="354a0-110">Compose or read</span></span>|

##### <a name="members-and-methods"></a><span data-ttu-id="354a0-111">メンバーとメソッド</span><span class="sxs-lookup"><span data-stu-id="354a0-111">Members and methods</span></span>

| <span data-ttu-id="354a0-112">メンバー</span><span class="sxs-lookup"><span data-stu-id="354a0-112">Member</span></span> | <span data-ttu-id="354a0-113">種類</span><span class="sxs-lookup"><span data-stu-id="354a0-113">Type</span></span> |
|--------|------|
| [<span data-ttu-id="354a0-114">AsyncResultStatus</span><span class="sxs-lookup"><span data-stu-id="354a0-114">AsyncResultStatus</span></span>](#asyncresultstatus-string) | <span data-ttu-id="354a0-115">メンバー</span><span class="sxs-lookup"><span data-stu-id="354a0-115">Member</span></span> |
| [<span data-ttu-id="354a0-116">CoercionType</span><span class="sxs-lookup"><span data-stu-id="354a0-116">CoercionType</span></span>](#coerciontype-string) | <span data-ttu-id="354a0-117">メンバー</span><span class="sxs-lookup"><span data-stu-id="354a0-117">Member</span></span> |
| [<span data-ttu-id="354a0-118">EventType</span><span class="sxs-lookup"><span data-stu-id="354a0-118">EventType</span></span>](#eventtype-string) | <span data-ttu-id="354a0-119">メンバー</span><span class="sxs-lookup"><span data-stu-id="354a0-119">Member</span></span> |
| [<span data-ttu-id="354a0-120">SourceProperty</span><span class="sxs-lookup"><span data-stu-id="354a0-120">SourceProperty</span></span>](#sourceproperty-string) | <span data-ttu-id="354a0-121">メンバー</span><span class="sxs-lookup"><span data-stu-id="354a0-121">Member</span></span> |

### <a name="namespaces"></a><span data-ttu-id="354a0-122">名前空間</span><span class="sxs-lookup"><span data-stu-id="354a0-122">Namespaces</span></span>

<span data-ttu-id="354a0-123">[コンテキスト](office.context.md): Outlook アドイン API で使用するための Office アドイン API のコンテキストの名前空間からの共有インターフェイスを提供します。</span><span class="sxs-lookup"><span data-stu-id="354a0-123">[context](office.context.md): Provides shared interfaces from the Office Add-ins API's context namespace for use in the Outlook add-in API.</span></span>

<span data-ttu-id="354a0-124">[MailboxEnums](/javascript/api/outlook/office.mailboxenums.attachmenttype):ItemType、EntityType、AttachmentType、RecipientType、ResponseType、および ItemNotificationMessageType 列挙型が含まれます。</span><span class="sxs-lookup"><span data-stu-id="354a0-124">[MailboxEnums](/javascript/api/outlook/office.mailboxenums.attachmenttype): Includes the ItemType, EntityType, AttachmentType, RecipientType, ResponseType, and ItemNotificationMessageType enumerations.</span></span>

### <a name="members"></a><span data-ttu-id="354a0-125">メンバー</span><span class="sxs-lookup"><span data-stu-id="354a0-125">Members</span></span>

####  <a name="asyncresultstatus-string"></a><span data-ttu-id="354a0-126">AsyncResultStatus :String</span><span class="sxs-lookup"><span data-stu-id="354a0-126">AsyncResultStatus :String</span></span>

<span data-ttu-id="354a0-127">非同期呼び出しの結果を指定します。</span><span class="sxs-lookup"><span data-stu-id="354a0-127">Specifies the result of an asynchronous call.</span></span>

##### <a name="type"></a><span data-ttu-id="354a0-128">型:</span><span class="sxs-lookup"><span data-stu-id="354a0-128">Type:</span></span>

*   <span data-ttu-id="354a0-129">String</span><span class="sxs-lookup"><span data-stu-id="354a0-129">String</span></span>

##### <a name="properties"></a><span data-ttu-id="354a0-130">プロパティ:</span><span class="sxs-lookup"><span data-stu-id="354a0-130">Properties:</span></span>

|<span data-ttu-id="354a0-131">名前</span><span class="sxs-lookup"><span data-stu-id="354a0-131">Name</span></span>| <span data-ttu-id="354a0-132">種類</span><span class="sxs-lookup"><span data-stu-id="354a0-132">Type</span></span>| <span data-ttu-id="354a0-133">説明</span><span class="sxs-lookup"><span data-stu-id="354a0-133">Description</span></span>|
|---|---|---|
|`Succeeded`| <span data-ttu-id="354a0-134">String</span><span class="sxs-lookup"><span data-stu-id="354a0-134">String</span></span>|<span data-ttu-id="354a0-135">呼び出しが成功しました。</span><span class="sxs-lookup"><span data-stu-id="354a0-135">The call succeeded.</span></span>|
|`Failed`| <span data-ttu-id="354a0-136">String</span><span class="sxs-lookup"><span data-stu-id="354a0-136">String</span></span>|<span data-ttu-id="354a0-137">呼び出しが失敗しました。</span><span class="sxs-lookup"><span data-stu-id="354a0-137">The call failed.</span></span>|

##### <a name="requirements"></a><span data-ttu-id="354a0-138">要件</span><span class="sxs-lookup"><span data-stu-id="354a0-138">Requirements</span></span>

|<span data-ttu-id="354a0-139">要件</span><span class="sxs-lookup"><span data-stu-id="354a0-139">Requirement</span></span>| <span data-ttu-id="354a0-140">値</span><span class="sxs-lookup"><span data-stu-id="354a0-140">Value</span></span>|
|---|---|
|[<span data-ttu-id="354a0-141">メールボックスの最小要件セットのバージョン</span><span class="sxs-lookup"><span data-stu-id="354a0-141">Minimum mailbox requirement set version</span></span>](/javascript/office/requirement-sets/outlook-api-requirement-sets)| <span data-ttu-id="354a0-142">1.0</span><span class="sxs-lookup"><span data-stu-id="354a0-142">1.0</span></span>|
|[<span data-ttu-id="354a0-143">適用可能な Outlook のモード</span><span class="sxs-lookup"><span data-stu-id="354a0-143">Applicable Outlook mode</span></span>](https://docs.microsoft.com/outlook/add-ins/#extension-points)| <span data-ttu-id="354a0-144">作成または読み取り</span><span class="sxs-lookup"><span data-stu-id="354a0-144">Compose or read</span></span>|

---

####  <a name="coerciontype-string"></a><span data-ttu-id="354a0-145">CoercionType :String</span><span class="sxs-lookup"><span data-stu-id="354a0-145">CoercionType :String</span></span>

<span data-ttu-id="354a0-146">呼び出されたメソッドによって返される、または設定されるデータを強制的に変換する方法を指定します。</span><span class="sxs-lookup"><span data-stu-id="354a0-146">Specifies how to coerce data returned or set by the invoked method.</span></span>

##### <a name="type"></a><span data-ttu-id="354a0-147">型:</span><span class="sxs-lookup"><span data-stu-id="354a0-147">Type:</span></span>

*   <span data-ttu-id="354a0-148">String</span><span class="sxs-lookup"><span data-stu-id="354a0-148">String</span></span>

##### <a name="properties"></a><span data-ttu-id="354a0-149">プロパティ:</span><span class="sxs-lookup"><span data-stu-id="354a0-149">Properties:</span></span>

|<span data-ttu-id="354a0-150">名前</span><span class="sxs-lookup"><span data-stu-id="354a0-150">Name</span></span>| <span data-ttu-id="354a0-151">種類</span><span class="sxs-lookup"><span data-stu-id="354a0-151">Type</span></span>| <span data-ttu-id="354a0-152">説明</span><span class="sxs-lookup"><span data-stu-id="354a0-152">Description</span></span>|
|---|---|---|
|`Html`| <span data-ttu-id="354a0-153">String</span><span class="sxs-lookup"><span data-stu-id="354a0-153">String</span></span>|<span data-ttu-id="354a0-154">HTML 形式で返されるデータを要求します。</span><span class="sxs-lookup"><span data-stu-id="354a0-154">Requests the data be returned in HTML format.</span></span>|
|`Text`| <span data-ttu-id="354a0-155">String</span><span class="sxs-lookup"><span data-stu-id="354a0-155">String</span></span>|<span data-ttu-id="354a0-156">テキスト形式で返されるデータを要求します。</span><span class="sxs-lookup"><span data-stu-id="354a0-156">Requests the data be returned in text format.</span></span>|

##### <a name="requirements"></a><span data-ttu-id="354a0-157">要件</span><span class="sxs-lookup"><span data-stu-id="354a0-157">Requirements</span></span>

|<span data-ttu-id="354a0-158">要件</span><span class="sxs-lookup"><span data-stu-id="354a0-158">Requirement</span></span>| <span data-ttu-id="354a0-159">値</span><span class="sxs-lookup"><span data-stu-id="354a0-159">Value</span></span>|
|---|---|
|[<span data-ttu-id="354a0-160">メールボックスの最小要件セットのバージョン</span><span class="sxs-lookup"><span data-stu-id="354a0-160">Minimum mailbox requirement set version</span></span>](/javascript/office/requirement-sets/outlook-api-requirement-sets)| <span data-ttu-id="354a0-161">1.0</span><span class="sxs-lookup"><span data-stu-id="354a0-161">1.0</span></span>|
|[<span data-ttu-id="354a0-162">適用可能な Outlook のモード</span><span class="sxs-lookup"><span data-stu-id="354a0-162">Applicable Outlook mode</span></span>](https://docs.microsoft.com/outlook/add-ins/#extension-points)| <span data-ttu-id="354a0-163">作成または読み取り</span><span class="sxs-lookup"><span data-stu-id="354a0-163">Compose or read</span></span>|

---

####  <a name="eventtype-string"></a><span data-ttu-id="354a0-164">EventType :String</span><span class="sxs-lookup"><span data-stu-id="354a0-164">EventType :String</span></span>

<span data-ttu-id="354a0-165">イベント ハンドラーに関連付けられているイベントを指定します。</span><span class="sxs-lookup"><span data-stu-id="354a0-165">Specifies the event associated with an event handler.</span></span>

##### <a name="type"></a><span data-ttu-id="354a0-166">型:</span><span class="sxs-lookup"><span data-stu-id="354a0-166">Type:</span></span>

*   <span data-ttu-id="354a0-167">String</span><span class="sxs-lookup"><span data-stu-id="354a0-167">String</span></span>

##### <a name="properties"></a><span data-ttu-id="354a0-168">プロパティ:</span><span class="sxs-lookup"><span data-stu-id="354a0-168">Properties:</span></span>

| <span data-ttu-id="354a0-169">名前</span><span class="sxs-lookup"><span data-stu-id="354a0-169">Name</span></span> | <span data-ttu-id="354a0-170">種類</span><span class="sxs-lookup"><span data-stu-id="354a0-170">Type</span></span> | <span data-ttu-id="354a0-171">説明</span><span class="sxs-lookup"><span data-stu-id="354a0-171">Description</span></span> |
|---|---|---|
|`ItemChanged`| <span data-ttu-id="354a0-172">String</span><span class="sxs-lookup"><span data-stu-id="354a0-172">String</span></span> | <span data-ttu-id="354a0-173">選択したアイテムが変更されました。</span><span class="sxs-lookup"><span data-stu-id="354a0-173">The selected item has changed.</span></span> |

##### <a name="requirements"></a><span data-ttu-id="354a0-174">要件</span><span class="sxs-lookup"><span data-stu-id="354a0-174">Requirements</span></span>

|<span data-ttu-id="354a0-175">要件</span><span class="sxs-lookup"><span data-stu-id="354a0-175">Requirement</span></span>| <span data-ttu-id="354a0-176">値</span><span class="sxs-lookup"><span data-stu-id="354a0-176">Value</span></span>|
|---|---|
|[<span data-ttu-id="354a0-177">メールボックスの最小要件セットのバージョン</span><span class="sxs-lookup"><span data-stu-id="354a0-177">Minimum mailbox requirement set version</span></span>](/javascript/office/requirement-sets/outlook-api-requirement-sets)| <span data-ttu-id="354a0-178">1.5</span><span class="sxs-lookup"><span data-stu-id="354a0-178">1.5</span></span> |
|[<span data-ttu-id="354a0-179">適用可能な Outlook のモード</span><span class="sxs-lookup"><span data-stu-id="354a0-179">Applicable Outlook mode</span></span>](https://docs.microsoft.com/outlook/add-ins/#extension-points)| <span data-ttu-id="354a0-180">作成または読み取り</span><span class="sxs-lookup"><span data-stu-id="354a0-180">Compose or read</span></span> |

---

####  <a name="sourceproperty-string"></a><span data-ttu-id="354a0-181">SourceProperty :String</span><span class="sxs-lookup"><span data-stu-id="354a0-181">SourceProperty :String</span></span>

<span data-ttu-id="354a0-182">呼び出されたメソッドによって返されるデータのソースを指定します。</span><span class="sxs-lookup"><span data-stu-id="354a0-182">Specifies the source of the data returned by the invoked method.</span></span>

##### <a name="type"></a><span data-ttu-id="354a0-183">型:</span><span class="sxs-lookup"><span data-stu-id="354a0-183">Type:</span></span>

*   <span data-ttu-id="354a0-184">String</span><span class="sxs-lookup"><span data-stu-id="354a0-184">String</span></span>

##### <a name="properties"></a><span data-ttu-id="354a0-185">プロパティ:</span><span class="sxs-lookup"><span data-stu-id="354a0-185">Properties:</span></span>

|<span data-ttu-id="354a0-186">名前</span><span class="sxs-lookup"><span data-stu-id="354a0-186">Name</span></span>| <span data-ttu-id="354a0-187">種類</span><span class="sxs-lookup"><span data-stu-id="354a0-187">Type</span></span>| <span data-ttu-id="354a0-188">説明</span><span class="sxs-lookup"><span data-stu-id="354a0-188">Description</span></span>|
|---|---|---|
|`Body`| <span data-ttu-id="354a0-189">String</span><span class="sxs-lookup"><span data-stu-id="354a0-189">String</span></span>|<span data-ttu-id="354a0-190">データのソースは、メッセージの本文です。</span><span class="sxs-lookup"><span data-stu-id="354a0-190">The source of the data is from the body of a message.</span></span>|
|`Subject`| <span data-ttu-id="354a0-191">String</span><span class="sxs-lookup"><span data-stu-id="354a0-191">String</span></span>|<span data-ttu-id="354a0-192">データのソースは、メッセージの件名です。</span><span class="sxs-lookup"><span data-stu-id="354a0-192">The source of the data is from the subject of a message.</span></span>|

##### <a name="requirements"></a><span data-ttu-id="354a0-193">要件</span><span class="sxs-lookup"><span data-stu-id="354a0-193">Requirements</span></span>

|<span data-ttu-id="354a0-194">要件</span><span class="sxs-lookup"><span data-stu-id="354a0-194">Requirement</span></span>| <span data-ttu-id="354a0-195">値</span><span class="sxs-lookup"><span data-stu-id="354a0-195">Value</span></span>|
|---|---|
|[<span data-ttu-id="354a0-196">メールボックスの最小要件セットのバージョン</span><span class="sxs-lookup"><span data-stu-id="354a0-196">Minimum mailbox requirement set version</span></span>](/javascript/office/requirement-sets/outlook-api-requirement-sets)| <span data-ttu-id="354a0-197">1.0</span><span class="sxs-lookup"><span data-stu-id="354a0-197">1.0</span></span>|
|[<span data-ttu-id="354a0-198">適用可能な Outlook のモード</span><span class="sxs-lookup"><span data-stu-id="354a0-198">Applicable Outlook mode</span></span>](https://docs.microsoft.com/outlook/add-ins/#extension-points)| <span data-ttu-id="354a0-199">作成または読み取り</span><span class="sxs-lookup"><span data-stu-id="354a0-199">Compose or read</span></span>|