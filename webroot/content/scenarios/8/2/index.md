---
title: Announce Review
description: 'The review service notifies the aggregator of a new review '
date: "2021-03-08"
scope: notify
sender: actor_1
pattern: announcement/announcement
payload:
    contexts: ["sorg","ldp","ietf","nat","nrr"]
    id: "urn:uuid:94ecae35-dcfd-4182-8550-22c7164fe23f"
    type: ["Announce","coar-notify:ReviewSuccess"]
    origin:
        lookup: "review-service"
    target:
        lookup: "repository"
    object:
        lookup: review
    actor:
        lookup: reviewer
---

