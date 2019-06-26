<!-- markdownlint-disable MD002 MD041 -->

<span data-ttu-id="d605a-101">В этом упражнении вы создадите регистрацию нового веб-приложения Azure AD с помощью центра администрирования Azure Active Directory.</span><span class="sxs-lookup"><span data-stu-id="d605a-101">In this exercise, you will create a new Azure AD web application registration using the Azure Active Directory admin center.</span></span>

1. <span data-ttu-id="d605a-102">Откройте браузер и перейдите к [Центру администрирования Azure Active Directory](https://aad.portal.azure.com).</span><span class="sxs-lookup"><span data-stu-id="d605a-102">Open a browser and navigate to the [Azure Active Directory admin center](https://aad.portal.azure.com).</span></span> <span data-ttu-id="d605a-103">Войдите с помощью **личной учетной записи** (т.е. учетной записи Microsoft) или **рабочей (учебной) учетной записи**.</span><span class="sxs-lookup"><span data-stu-id="d605a-103">Login using a **personal account** (aka: Microsoft Account) or **Work or School Account**.</span></span>

1. <span data-ttu-id="d605a-104">Выберите **Azure Active Directory** в левой панели навигации, а затем выберите **Регистрация приложений** в разделе **Управление**.</span><span class="sxs-lookup"><span data-stu-id="d605a-104">Select **Azure Active Directory** in the left-hand navigation, then select **App registrations** under **Manage**.</span></span>

    ![<span data-ttu-id="d605a-105">Снимок экрана с регистрациями приложений</span><span class="sxs-lookup"><span data-stu-id="d605a-105">A screenshot of the App registrations</span></span> ](./images/aad-portal-app-registrations.png)

1. <span data-ttu-id="d605a-106">Выберите **Новая регистрация**.</span><span class="sxs-lookup"><span data-stu-id="d605a-106">Select **New registration**.</span></span> <span data-ttu-id="d605a-107">На странице**Зарегистрировать приложение** задайте необходимые значения следующим образом.</span><span class="sxs-lookup"><span data-stu-id="d605a-107">On the **Register an application** page, set the values as follows.</span></span>

    - <span data-ttu-id="d605a-108">Введите **имя** `React Graph Tutorial`.</span><span class="sxs-lookup"><span data-stu-id="d605a-108">Set **Name** to `React Graph Tutorial`.</span></span>
    - <span data-ttu-id="d605a-109">Введите **поддерживаемые типы учетных записей** для **учетных записей в любом каталоге организаций и личных учетных записей Microsoft**.</span><span class="sxs-lookup"><span data-stu-id="d605a-109">Set **Supported account types** to **Accounts in any organizational directory and personal Microsoft accounts**.</span></span>
    - <span data-ttu-id="d605a-110">В разделе **URI адрес перенаправления** введите значение в первом раскрывающемся списке `Web` и задайте значение `http://localhost:3000`.</span><span class="sxs-lookup"><span data-stu-id="d605a-110">Under **Redirect URI**, set the first drop-down to `Web` and set the value to `http://localhost:3000`.</span></span>

    ![Снимок страницы "регистрация приложения"](./images/aad-register-an-app.png)

1. <span data-ttu-id="d605a-112">Выберите **Зарегистрировать**.</span><span class="sxs-lookup"><span data-stu-id="d605a-112">Choose **Register**.</span></span> <span data-ttu-id="d605a-113">На странице **учебника "реагирующий график** " СКОПИРУЙТЕ значение **идентификатора Application (Client)** и сохраните его, он понадобится на следующем шаге.</span><span class="sxs-lookup"><span data-stu-id="d605a-113">On the **React Graph Tutorial** page, copy the value of the **Application (client) ID** and save it, you will need it in the next step.</span></span>

    ![Снимок экрана с ИДЕНТИФИКАТОРом приложения для новой регистрации приложения](./images/aad-application-id.png)

1. <span data-ttu-id="d605a-115">Выберите **Проверка подлинности** в разделе **Управление**.</span><span class="sxs-lookup"><span data-stu-id="d605a-115">Select **Authentication** under **Manage**.</span></span> <span data-ttu-id="d605a-116">Нахождение неявного раздела **предоставления** и включение **маркеров доступа** и **маркеров ID**.</span><span class="sxs-lookup"><span data-stu-id="d605a-116">Locate the **Implicit grant** section and enable **Access tokens** and **ID tokens**.</span></span> <span data-ttu-id="d605a-117">Нажмите кнопку **Сохранить**.</span><span class="sxs-lookup"><span data-stu-id="d605a-117">Choose **Save**.</span></span>

    ![Снимок экрана с неявным разделом предоставления](./images/aad-implicit-grant.png)
