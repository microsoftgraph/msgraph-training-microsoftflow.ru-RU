# <a name="microsoft-graph-training-module---create-a-microsoft-graph-json-batch-custom-connector-for-microsoft-flow--azure-logic-apps"></a><span data-ttu-id="c5ef6-101">Модуль Microsoft Graph Training — создание настраиваемого соединителя Microsoft Graph JSON для приложений логики Microsoft Flow _Амп_ Azure</span><span class="sxs-lookup"><span data-stu-id="c5ef6-101">Microsoft Graph Training Module - Create a Microsoft Graph JSON Batch Custom Connector for Microsoft Flow & Azure Logic Apps</span></span>

<span data-ttu-id="c5ef6-102">В этом модуле вы узнаете, как работать с API пакетной обработки REST JSON для Microsoft Graph для доступа к данным в Office 365.</span><span class="sxs-lookup"><span data-stu-id="c5ef6-102">This module will introduce you to working with the Microsoft Graph JSON Batching REST API to access data in Office 365.</span></span> <span data-ttu-id="c5ef6-103">Вы узнаете, как создать и настроить настраиваемый соединитель для Flow, получить доступ к пакету API Microsoft Graph JSON и использовать настраиваемый соединитель в процессе создания команды Майкрософт.</span><span class="sxs-lookup"><span data-stu-id="c5ef6-103">You will learn how to create and configure a custom connector for Flow, access the the Microsoft graph JSON Batch API, and use the custom connector in a Flow to create a Microsoft Team.</span></span>

## <a name="lab---create-a-microsoft-graph-json-batch-custom-connector-for-microsoft-flow--azure-logic-apps"></a><span data-ttu-id="c5ef6-104">Лаборатория: Создание настраиваемого соединителя Microsoft Graph JSON для приложений логики Microsoft Flow _Амп_ Azure</span><span class="sxs-lookup"><span data-stu-id="c5ef6-104">Lab - Create a Microsoft Graph JSON Batch Custom Connector for Microsoft Flow & Azure Logic Apps</span></span>

<span data-ttu-id="c5ef6-105">В этой лабораторной работе вы будете использовать API пакетной обработки REST JSON для Microsoft Graph для создания настраиваемого соединителя и приложения для передачи данных.</span><span class="sxs-lookup"><span data-stu-id="c5ef6-105">In this lab you will leverage the Microsoft Graph JSON Batching REST API to create a Custom Connector and Flow application.</span></span>

- [<span data-ttu-id="c5ef6-106">Руководство по работе с Microsoft Graph</span><span class="sxs-lookup"><span data-stu-id="c5ef6-106">Flow Microsoft Graph tutorial</span></span>](https://docs.microsoft.com/graph/training/flow-tutorial)

## <a name="contributors"></a><span data-ttu-id="c5ef6-107">Авторы</span><span class="sxs-lookup"><span data-stu-id="c5ef6-107">Contributors</span></span>

| <span data-ttu-id="c5ef6-108">Роли</span><span class="sxs-lookup"><span data-stu-id="c5ef6-108">Roles</span></span> | <span data-ttu-id="c5ef6-109">Authors (s)</span><span class="sxs-lookup"><span data-stu-id="c5ef6-109">Author(s)</span></span> |
| ------| ----------|
| <span data-ttu-id="c5ef6-110">Лабораторные руководства</span><span class="sxs-lookup"><span data-stu-id="c5ef6-110">Lab Manuals</span></span> | <span data-ttu-id="c5ef6-111">Джон Лиу (Майкрософт MVP, Шарепоинтгурус) @johnnliu</span><span class="sxs-lookup"><span data-stu-id="c5ef6-111">John Liu (Microsoft MVP, SharePointGurus ) @johnnliu</span></span> |
| <span data-ttu-id="c5ef6-112">Лабораторные руководства</span><span class="sxs-lookup"><span data-stu-id="c5ef6-112">Lab Manuals</span></span> | <span data-ttu-id="c5ef6-113">Скелли (Сривилл) @pskelly</span><span class="sxs-lookup"><span data-stu-id="c5ef6-113">Pete Skelly (ThreeWill) @pskelly</span></span> |

## <a name="version-history"></a><span data-ttu-id="c5ef6-114">Журнал версий</span><span class="sxs-lookup"><span data-stu-id="c5ef6-114">Version history</span></span>

| <span data-ttu-id="c5ef6-115">Version</span><span class="sxs-lookup"><span data-stu-id="c5ef6-115">Version</span></span> | <span data-ttu-id="c5ef6-116">Дата</span><span class="sxs-lookup"><span data-stu-id="c5ef6-116">Date</span></span> | <span data-ttu-id="c5ef6-117">Comments</span><span class="sxs-lookup"><span data-stu-id="c5ef6-117">Comments</span></span> |
| ------- | -----| -------- |
| <span data-ttu-id="c5ef6-118">1.2</span><span class="sxs-lookup"><span data-stu-id="c5ef6-118">1.2</span></span> | <span data-ttu-id="c5ef6-119">27 ноября 2018 г.</span><span class="sxs-lookup"><span data-stu-id="c5ef6-119">November 27, 2018</span></span> | <span data-ttu-id="c5ef6-120">Подключение к docs.microsoft.com/graph</span><span class="sxs-lookup"><span data-stu-id="c5ef6-120">Onboarded to docs.microsoft.com/graph</span></span> |
| <span data-ttu-id="c5ef6-121">1.1</span><span class="sxs-lookup"><span data-stu-id="c5ef6-121">1.1</span></span> | <span data-ttu-id="c5ef6-122">07 ноября 2018 г.</span><span class="sxs-lookup"><span data-stu-id="c5ef6-122">November 07, 2018</span></span> | <span data-ttu-id="c5ef6-123">Добавлен шаг 6 контента для вызова нескольких операций</span><span class="sxs-lookup"><span data-stu-id="c5ef6-123">Added step 6 content for calling multiple operations</span></span> |
| <span data-ttu-id="c5ef6-124">1.0</span><span class="sxs-lookup"><span data-stu-id="c5ef6-124">1.0</span></span> | <span data-ttu-id="c5ef6-125">22 октября 2018 г.</span><span class="sxs-lookup"><span data-stu-id="c5ef6-125">October 22, 2018</span></span> | <span data-ttu-id="c5ef6-126">Добавление сведений о продуктах, связанных с Microsoft Graph.</span><span class="sxs-lookup"><span data-stu-id="c5ef6-126">Add Microsoft Graph related product breakouts.</span></span> |

## <a name="disclaimer"></a><span data-ttu-id="c5ef6-127">Заявление об отказе</span><span class="sxs-lookup"><span data-stu-id="c5ef6-127">Disclaimer</span></span>

<span data-ttu-id="c5ef6-128">**Этот код предоставляется без каких *-* либо гарантий, явных или подразумеваемых, включая любые подразумеваемые гарантии пригодности для конкретной цели, ПРИГОДности к отДЕЛЬному ОБЪЕМу или ненарушениям.**</span><span class="sxs-lookup"><span data-stu-id="c5ef6-128">**THIS CODE IS PROVIDED *AS IS* WITHOUT WARRANTY OF ANY KIND, EITHER EXPRESS OR IMPLIED, INCLUDING ANY IMPLIED WARRANTIES OF FITNESS FOR A PARTICULAR PURPOSE, MERCHANTABILITY, OR NON-INFRINGEMENT.**</span></span>