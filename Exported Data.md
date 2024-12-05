---
deleted: true
tags: [Import-240f]
title: Exported Data
created: '2024-12-04T14:00:42.515Z'
modified: '2024-12-05T09:46:21.827Z'
---

# Exported Data


    Return-Path: [M.vanBijsterveld@Belcombinatie.nl](mailto:M.vanBijsterveld@Belcombinatie.nl)
    X-Original-To:
    Delivered-To:
    Authentication-Results: [mail.protonmail.ch](http://mail.protonmail.ch); dkim=pass (Good 1024 bit
    rsa-sha256 signature) header.d=[belcombinatie.nl](http://belcombinatie.nl) header.a=rsa-sha256
    Authentication-Results: [mail.protonmail.ch](http://mail.protonmail.ch); dmarc=pass (p=reject dis=none)
    header.from=[Belcombinatie.nl](http://Belcombinatie.nl)
    Authentication-Results: [mail.protonmail.ch](http://mail.protonmail.ch); spf=pass smtp.mailfrom=[Belcombinatie.nl](http://Belcombinatie.nl)
    Authentication-Results: [mail.protonmail.ch](http://mail.protonmail.ch); arc=pass smtp.remote-ip=40.107.104.94
    arc.chain=:[microsoft.com](http://microsoft.com)
    Authentication-Results: [mail.protonmail.ch](http://mail.protonmail.ch); dkim=pass (1024-bit key)
    header.d=[belcombinatie.nl](http://belcombinatie.nl) [header.i=@belcombinatie.nl](mailto:header.i=@belcombinatie.nl) header.b="VL+QcZuE"
    Received: from [EUR03-DBA-obe.outbound.protection.outlook.com](http://EUR03-DBA-obe.outbound.protection.outlook.com)
    ([mail-dbaeur03on2094.outbound.protection.outlook.com](http://mail-dbaeur03on2094.outbound.protection.outlook.com) \[40.107.104.94\]) (using TLSv1.2
    with cipher ECDHE-RSA-AES256-GCM-SHA384 (256/256 bits)) (No client certificate

  
    Return-Path: [Noreply@Belcombinatie.nl](mailto:Noreply@Belcombinatie.nl)

    Authentication-Results: [mail.protonmail.ch](http://mail.protonmail.ch); dkim=pass (Good 1024 bit
    rsa-sha256 signature) header.d=[belcombinatie.nl](http://belcombinatie.nl) header.a=rsa-sha256
    Authentication-Results: [mail.protonmail.ch](http://mail.protonmail.ch); dmarc=pass (p=reject dis=none)
    header.from=[Belcombinatie.nl](http://Belcombinatie.nl)
    Authentication-Results: [mail.protonmail.ch](http://mail.protonmail.ch); spf=pass smtp.mailfrom=[Belcombinatie.nl](http://Belcombinatie.nl)
    Authentication-Results: [mail.protonmail.ch](http://mail.protonmail.ch); arc=pass smtp.remote-ip=40.107.7.104
    arc.chain=:[microsoft.com](http://microsoft.com)
    Authentication-Results: [mail.protonmail.ch](http://mail.protonmail.ch); dkim=pass (1024-bit key)
    header.d=[belcombinatie.nl](http://belcombinatie.nl) [header.i=@belcombinatie.nl](mailto:header.i=@belcombinatie.nl) header.b="CPaaqnkD"
    Received: from [EUR04-HE1-obe.outbound.protection.outlook.com](http://EUR04-HE1-obe.outbound.protection.outlook.com)
    ([mail-he1eur04on2104.outbound.protection.outlook.com](http://mail-he1eur04on2104.outbound.protection.outlook.com) \[40.107.7.104\]) (using TLSv1.2 with
    cipher ECDHE-RSA-AES256-GCM-SHA384 (256/256 bits)) (No client certificate requested) by
    [mailin038.protonmail.ch](http://mailin038.protonmail.ch) (Postfix) with ESMTPS id 4VtDFQ39rfz6g for
    [goija@protonmail.com](mailto:goija@protonmail.com); Mon,
    3 Jun 2024 12:54:18 +0000 (UTC)
    Received: from [VI1PR01MB6318.eurprd01.prod.exchangelabs.com](http://VI1PR01MB6318.eurprd01.prod.exchangelabs.com) (2603:10a6:800:153::12) by
    [AM9PR01MB8332.eurprd01.prod.exchangelabs.com](http://AM9PR01MB8332.eurprd01.prod.exchangelabs.com) (2603:10a6:20b:43b::17) with Microsoft SMTP
    Server (version=TLS1_2, cipher=TLS_ECDHE_RSA_WITH_AES_256_GCM_SHA384) id 15.20.7633.27;
    Mon, 3 Jun 2024 12:54:11 +0000
    Received: from [VI1PR01MB6318.eurprd01.prod.exchangelabs.com](http://VI1PR01MB6318.eurprd01.prod.exchangelabs.com) (\[fe80::2330:b694:f2eb:aac3\])
    by [VI1PR01MB6318.eurprd01.prod.exchangelabs.com](http://VI1PR01MB6318.eurprd01.prod.exchangelabs.com) (\[fe80::2330:b694:f2eb:aac3%6\]) with
    mapi id 15.20.7633.021; Mon, 3 Jun 2024 12:54:10 +0000
    Arc-Seal: i=1; a=rsa-sha256; s=arcselector9901; d=[microsoft.com](http://microsoft.com); cv=none;

      Return-Path: [M.vanBijsterveld@Belcombinatie.nl](mailto:M.vanBijsterveld@Belcombinatie.nl)

    Authentication-Results: [mail.protonmail.ch](http://mail.protonmail.ch); dkim=pass (Good 1024 bit
    rsa-sha256 signature) header.d=[belcombinatie.nl](http://belcombinatie.nl) header.a=rsa-sha256
    Authentication-Results: [mail.protonmail.ch](http://mail.protonmail.ch); dmarc=pass (p=reject dis=none)
    header.from=[Belcombinatie.nl](http://Belcombinatie.nl)
    Authentication-Results: [mail.protonmail.ch](http://mail.protonmail.ch); spf=pass smtp.mailfrom=[Belcombinatie.nl](http://Belcombinatie.nl)
    Authentication-Results: [mail.protonmail.ch](http://mail.protonmail.ch); arc=pass smtp.remote-ip=40.107.103.129
    arc.chain=:[microsoft.com](http://microsoft.com)
    Authentication-Results: [mail.protonmail.ch](http://mail.protonmail.ch); dkim=pass (1024-bit key)
    header.d=[belcombinatie.nl](http://belcombinatie.nl) [header.i=@belcombinatie.nl](mailto:header.i=@belcombinatie.nl) header.b="epSOhsOS"
    Received: from [EUR03-VI1-obe.outbound.protection.outlook.com](http://EUR03-VI1-obe.outbound.protection.outlook.com)
    ([mail-vi1eur03on2129.outbound.protection.outlook.com](http://mail-vi1eur03on2129.outbound.protection.outlook.com) \[40.107.103.129\]) (using TLSv1.3
    with cipher TLS_AES_256_GCM_SHA384 (256/256 bits)
    key-exchange ECDHE (P-384) server-signature RSA-PSS (4096 bits) server-digest SHA256)
    (No client certificate requested) by [mailin053.protonmail.ch](http://mailin053.protonmail.ch) (Postfix) with ESMTPS id

    2 Dec 2024 09:17:48 +0000 (UTC)
    Received: from [AS1PR01MB9490.eurprd01.prod.exchangelabs.com](http://AS1PR01MB9490.eurprd01.prod.exchangelabs.com) (2603:10a6:20b:4d2::17) by
    [VI1PR01MB6943.eurprd01.prod.exchangelabs.com](http://VI1PR01MB6943.eurprd01.prod.exchangelabs.com) (2603:10a6:800:199::7) with Microsoft SMTP
    Server (version=TLS1_2, cipher=TLS_ECDHE_RSA_WITH_AES_256_GCM_SHA384) id 15.20.8207.18;
    Mon, 2 Dec 2024 09:17:38 +0000
    Received: from [AS1PR01MB9490.eurprd01.prod.exchangelabs.com](http://AS1PR01MB9490.eurprd01.prod.exchangelabs.com) (\[fe80::523c:d31:f3fb:80ca\])
    by [AS1PR01MB9490.eurprd01.prod.exchangelabs.com](http://AS1PR01MB9490.eurprd01.prod.exchangelabs.com) (\[fe80::523c:d31:f3fb:80ca%7\]) with mapi
    id 15.20.8207.017; Mon, 2 Dec 2024 09:17:38 +0000
    Arc-Seal: i=1; a=rsa-sha256; s=arcselector10001; d=[microsoft.com](http://microsoft.com); cv=none;
    b=o5K1vVI/S6HfCADBuXyE3lxwNKb5kuXEKdifJ+ogZrS8ldI7gpzQjrIvlVVrEPn35geMBQXA92IEyNC2gquJoNXC9tj8I5Hp+FSUetiO5dySHJ77b6GkhAAS3nYwDtVynD5MjLyfjR93rLeaHQRRPvlZcXpOXvhpAQreYDOL7hSLtKNRx9C6/tcPuDttTtLEhedyWwTTrtcH6PaMLGbCUx8iHsYdpfAsqtI2k2fkQ04igrkQX5ZhviMK+mylkCE9FGV0Vd5qGVudoHjbaSKiNTgNz2vZ2oZ9F7mbp1wG14MJt6bqlrrF71ZSszpOQuxE/LxWCC26DkAzbfxS5Uo+bA==
    Arc-Message-Signature: i=1; a=rsa-sha256; c=relaxed/relaxed; d=[microsoft.com](http://microsoft.com);
    s=arcselector10001;
    h=From:Date:Subject:Message-ID:Content-Type:MIME-Version:X-MS-Exchange-AntiSpam-MessageData-ChunkCount:X-MS-Exchange-AntiSpam-MessageData-0:X-MS-Exchange-AntiSpam-MessageData-1;
    bh=s00RY+K/c0upp69FRa1MtMAT5AAnKMtncwl6742Waec=;

    Return-Path: [M.vanBijsterveld@Belcombinatie.nl](mailto:M.vanBijsterveld@Belcombinatie.nl)

    Authentication-Results: [mail.protonmail.ch](http://mail.protonmail.ch); dkim=pass (Good 1024 bit
    rsa-sha256 signature) header.d=[belcombinatie.nl](http://belcombinatie.nl) header.a=rsa-sha256
    Authentication-Results: [mail.protonmail.ch](http://mail.protonmail.ch); dmarc=pass (p=reject dis=none)
    header.from=[Belcombinatie.nl](http://Belcombinatie.nl)
    Authentication-Results: [mail.protonmail.ch](http://mail.protonmail.ch); spf=pass smtp.mailfrom=[Belcombinatie.nl](http://Belcombinatie.nl)
    Authentication-Results: [mail.protonmail.ch](http://mail.protonmail.ch); arc=pass smtp.remote-ip=40.107.103.129
    arc.chain=:[microsoft.com](http://microsoft.com)
    Authentication-Results: [mail.protonmail.ch](http://mail.protonmail.ch); dkim=pass (1024-bit key)
    header.d=[belcombinatie.nl](http://belcombinatie.nl) [header.i=@belcombinatie.nl](mailto:header.i=@belcombinatie.nl) header.b="epSOhsOS"
    Received: from [EUR03-VI1-obe.outbound.protection.outlook.com](http://EUR03-VI1-obe.outbound.protection.outlook.com)
    ([mail-vi1eur03on2129.outbound.protection.outlook.com](http://mail-vi1eur03on2129.outbound.protection.outlook.com) \[40.107.103.129\]) (using TLSv1.3
    with cipher TLS_AES_256_GCM_SHA384 (256/256 bits)
    key-exchange ECDHE (P-384) server-signature RSA-PSS (4096 bits) server-digest SHA256)
    (No client certificate requested) by [mailin053.protonmail.ch](http://mailin053.protonmail.ch) (Postfix) with ESMTPS id
    4Y1yqd1MRyz6F for [riannegoijarts@pm.me](mailto:riannegoijarts@pm.me); Mon,
    2 Dec 2024 09:17:48 +0000 (UTC)
    Received: from [AS1PR01MB9490.eurprd01.prod.exchangelabs.com](http://AS1PR01MB9490.eurprd01.prod.exchangelabs.com) (2603:10a6:20b:4d2::17) by
    [VI1PR01MB6943.eurprd01.prod.exchangelabs.com](http://VI1PR01MB6943.eurprd01.prod.exchangelabs.com) (2603:10a6:800:199::7) with Microsoft SMTP
    Server (version=TLS1_2, cipher=TLS_ECDHE_RSA_WITH_AES_256_GCM_SHA384) id 15.20.8207.18;
    Mon, 2 Dec 2024 09:17:38 +0000
    Received: from [AS1PR01MB9490.eurprd01.prod.exchangelabs.com](http://AS1PR01MB9490.eurprd01.prod.exchangelabs.com) (\[fe80::523c:d31:f3fb:80ca\])
    by [AS1PR01MB9490.eurprd01.prod.exchangelabs.com](http://AS1PR01MB9490.eurprd01.prod.exchangelabs.com) (\[fe80::523c:d31:f3fb:80ca%7\]) with mapi
    id 15.20.8207.017; Mon, 2 Dec 2024 09:17:38 +0000
    Arc-Seal: i=1; a=rsa-sha256; s=arcselector10001; d=[microsoft.com](http://microsoft.com); cv=none;
    b=o5K1vVI/S6HfCADBuXyE3lxwNKb5kuXEKdifJ+ogZrS8ldI7gpzQjrIvlVVrEPn35geMBQXA92IEyNC2gquJoNXC9tj8I5Hp+FSUetiO5dySHJ77b6GkhAAS3nYwDtVynD5MjLyfjR93rLeaHQRRPvlZcXpOXvhpAQreYDOL7hSLtKNRx9C6/tcPuDttTtLEhedyWwTTrtcH6PaMLGbCUx8iHsYdpfAsqtI2k2fkQ04igrkQX5ZhviMK+mylkCE9FGV0Vd5qGVudoHjbaSKiNTgNz2vZ2oZ9F7mbp1wG14MJt6bqlrrF71ZSszpOQuxE/LxWCC26DkAzbfxS5Uo+bA==
    Arc-Message-Signature: i=1; a=rsa-sha256; c=relaxed/relaxed; d=[microsoft.com](http://microsoft.com);
    s=arcselector10001;
    h=From:Date:Subject:Message-ID:Content-Type:MIME-Version:X-MS-Exchange-AntiSpam-MessageData-ChunkCount:X-MS-Exchange-AntiSpam-MessageData-0:X-MS-Exchange-AntiSpam-MessageData-1;
    bh=s00RY+K/c0upp69FRa1MtMAT5AAnKMtncwl6742Waec=;
    b=PWgYAVnvcbh9gQw291pWSlr82KfuvMENCddduYXuvfudNfb00bwWqQzHIY4UCUaYGnMrC0ATKnMZwQz//H7ul/DrADg5WfDXnqEhpjOuxfZNxHmvjyaqLRDknWfBPk2v7IpKNfQfeSozrQcsKBlwnVXXgVPjQTm5hUN6VsXUxSkm860pjV9JNX5XpazcUoURZcHTnMGK1f3g4Zf6AOYbBC8P4A09Ew7FVwhjakoQT3Y7mE/2bnOREzi8t2GRDo9FIs8EDtlaLJS+u8MqsOJ6nJMWQAVZ9aDjx0YPzW+SRrIntmPD3ATC/LxNf7XlUO/tnhm/tDbSb8SZCv/Xps05rg==
    Arc-Authentication-Results: i=1; [mx.microsoft.com](http://mx.microsoft.com) 1; spf=pass
    smtp.mailfrom=[belcombinatie.nl](http://belcombinatie.nl); dmarc=pass action=none header.from=[belcombinatie.nl](http://belcombinatie.nl);
    dkim=pass header.d=[belcombinatie.nl](http://belcombinatie.nl); arc=none
    Dkim-Signature: v=1; a=rsa-sha256; c=relaxed/relaxed; d=[belcombinatie.nl](http://belcombinatie.nl); s=selector1;
    h=From:Date:Subject:Message-ID:Content-Type:MIME-Version:X-MS-Exchange-SenderADCheck;
    bh=s00RY+K/c0upp69FRa1MtMAT5AAnKMtncwl6742Waec=;
    b=epSOhsOSQh28H60XW5Z29Mf3oGCkXRQV2yBl7XC6ULeNyyokknZ25cBl8GlawymYWPlhHzCuksx1qpPbWi8yPILzX9FJF3S9NMh/ZkKyY4l69GfR4ewi6K3cr4sK6NUp6XXEjkTtHas+Ye2e2T7hj3jdXgUOateyt7l23orAQB4=
    From: Melissa van Bijsterveld [M.vanBijsterveld@Belcombinatie.nl](mailto:M.vanBijsterveld@Belcombinatie.nl)

    Cc: Hans Haverkamp [H.Haverkamp@Belcombinatie.nl](mailto:H.Haverkamp@Belcombinatie.nl)
    Subject: verslag gesprek 28/11
    Thread-Topic: verslag gesprek 28/11
    Thread-Index: AdtEjHI+z/wa+K9XSE+XnPmu+3OTVQ==
    Date: Mon, 02 Dec 2024 09:17:37 +0000
