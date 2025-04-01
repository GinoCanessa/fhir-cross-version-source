Comparison of 
Generated at Tuesday, April 1, 2025 1:39:33 PM

### LinkRelationTypes

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| VS Name | LinkRelationTypes |
| Canonical URL | `http://hl7.org/fhir/ValueSet/iana-link-relations` |
| Version | 5.0.0 |
| Description | Link Relation Types defined at https://www.iana.org/assignments/link-relations/link-relations.xhtml#link-relations-1 |
| Status | `Active` |
| Has Escape Valve Code | `False` |
| Database Key | `4605` |
| Database Concept Count | `120` |
| Database Active Concept Count | `120` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Bundle` | `Bundle.link.relation` | `http://hl7.org/fhir/ValueSet/iana-link-relations\|5.0.0` | `Required` | See http://www.iana.org/assignments/link-relations/link-relations.xhtml#link-relations-1 |

### Referenced Systems

* `http://hl7.org/fhir/CodeSystem/iana-link-relations`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://hl7.org/fhir/CodeSystem/iana-link-relations` | `P3Pv1` | Refers to a P3P privacy policy for the context. |
| `http://hl7.org/fhir/CodeSystem/iana-link-relations` | `about` | Refers to a resource that is the subject of the link's context. |
| `http://hl7.org/fhir/CodeSystem/iana-link-relations` | `acl` | Asserts that the link target provides an access control description for the link context. |
| `http://hl7.org/fhir/CodeSystem/iana-link-relations` | `alternate` | Refers to a substitute for this context |
| `http://hl7.org/fhir/CodeSystem/iana-link-relations` | `amphtml` | Used to reference alternative content that uses the AMP profile of the HTML format. |
| `http://hl7.org/fhir/CodeSystem/iana-link-relations` | `appendix` | Refers to an appendix. |
| `http://hl7.org/fhir/CodeSystem/iana-link-relations` | `apple-touch-icon` | Refers to an icon for the context. Synonym for icon. |
| `http://hl7.org/fhir/CodeSystem/iana-link-relations` | `apple-touch-startup-image` | Refers to a launch screen for the context. |
| `http://hl7.org/fhir/CodeSystem/iana-link-relations` | `archives` | Refers to a collection of records, documents, or other<br/>      materials of historical interest. |
| `http://hl7.org/fhir/CodeSystem/iana-link-relations` | `author` | Refers to the context's author. |
| `http://hl7.org/fhir/CodeSystem/iana-link-relations` | `blocked-by` | Identifies the entity that blocks access to a resource<br/>      following receipt of a legal demand. |
| `http://hl7.org/fhir/CodeSystem/iana-link-relations` | `bookmark` | Gives a permanent link to use for bookmarking purposes. |
| `http://hl7.org/fhir/CodeSystem/iana-link-relations` | `canonical` | Designates the preferred version of a resource (the IRI and its contents). |
| `http://hl7.org/fhir/CodeSystem/iana-link-relations` | `chapter` | Refers to a chapter in a collection of resources. |
| `http://hl7.org/fhir/CodeSystem/iana-link-relations` | `cite-as` | Indicates that the link target is preferred over the link context for the purpose of permanent citation. |
| `http://hl7.org/fhir/CodeSystem/iana-link-relations` | `collection` | The target IRI points to a resource which represents the collection resource for the context IRI. |
| `http://hl7.org/fhir/CodeSystem/iana-link-relations` | `contents` | Refers to a table of contents. |
| `http://hl7.org/fhir/CodeSystem/iana-link-relations` | `convertedFrom` | The document linked to was later converted to the<br/>      document that contains this link relation.  For example, an RFC can<br/>      have a link to the Internet-Draft that became the RFC; in that case,<br/>      the link relation would be "convertedFrom". |
| `http://hl7.org/fhir/CodeSystem/iana-link-relations` | `copyright` | Refers to a copyright statement that applies to the<br/>    link's context. |
| `http://hl7.org/fhir/CodeSystem/iana-link-relations` | `create-form` | The target IRI points to a resource where a submission form can be obtained. |
| `http://hl7.org/fhir/CodeSystem/iana-link-relations` | `current` | Refers to a resource containing the most recent<br/>      item(s) in a collection of resources. |
| `http://hl7.org/fhir/CodeSystem/iana-link-relations` | `describedby` | Refers to a resource providing information about the<br/>      link's context. |
| `http://hl7.org/fhir/CodeSystem/iana-link-relations` | `describes` | The relationship A 'describes' B asserts that<br/>      resource A provides a description of resource B. There are no<br/>      constraints on the format or representation of either A or B,<br/>      neither are there any further constraints on either resource. |
| `http://hl7.org/fhir/CodeSystem/iana-link-relations` | `disclosure` | Refers to a list of patent disclosures made with respect to <br/>      material for which 'disclosure' relation is specified. |
| `http://hl7.org/fhir/CodeSystem/iana-link-relations` | `dns-prefetch` | Used to indicate an origin that will be used to fetch required <br/>      resources for the link context, and that the user agent ought to resolve <br/>      as early as possible. |
| `http://hl7.org/fhir/CodeSystem/iana-link-relations` | `duplicate` | Refers to a resource whose available representations<br/>      are byte-for-byte identical with the corresponding representations of<br/>      the context IRI. |
| `http://hl7.org/fhir/CodeSystem/iana-link-relations` | `edit` | Refers to a resource that can be used to edit the<br/>      link's context. |
| `http://hl7.org/fhir/CodeSystem/iana-link-relations` | `edit-form` | The target IRI points to a resource where a submission form for<br/>      editing associated resource can be obtained. |
| `http://hl7.org/fhir/CodeSystem/iana-link-relations` | `edit-media` | Refers to a resource that can be used to edit media<br/>      associated with the link's context. |
| `http://hl7.org/fhir/CodeSystem/iana-link-relations` | `enclosure` | Identifies a related resource that is potentially<br/>      large and might require special handling. |
| `http://hl7.org/fhir/CodeSystem/iana-link-relations` | `external` | Refers to a resource that is not part of the same site as the current context. |
| `http://hl7.org/fhir/CodeSystem/iana-link-relations` | `first` | An IRI that refers to the furthest preceding resource<br/>    in a series of resources. |
| `http://hl7.org/fhir/CodeSystem/iana-link-relations` | `glossary` | Refers to a glossary of terms. |
| `http://hl7.org/fhir/CodeSystem/iana-link-relations` | `help` | Refers to context-sensitive help. |
| `http://hl7.org/fhir/CodeSystem/iana-link-relations` | `hosts` | Refers to a resource hosted by the server indicated by<br/>      the link context. |
| `http://hl7.org/fhir/CodeSystem/iana-link-relations` | `hub` | Refers to a hub that enables registration for<br/>    notification of updates to the context. |
| `http://hl7.org/fhir/CodeSystem/iana-link-relations` | `icon` | Refers to an icon representing the link's context. |
| `http://hl7.org/fhir/CodeSystem/iana-link-relations` | `index` | Refers to an index. |
| `http://hl7.org/fhir/CodeSystem/iana-link-relations` | `intervalAfter` | refers to a resource associated with a time interval that ends before the beginning of the time interval associated with the context resource |
| `http://hl7.org/fhir/CodeSystem/iana-link-relations` | `intervalBefore` | refers to a resource associated with a time interval that begins after the end of the time interval associated with the context resource |
| `http://hl7.org/fhir/CodeSystem/iana-link-relations` | `intervalContains` | refers to a resource associated with a time interval that begins after the beginning of the time interval associated with the context resource, and ends before the end of the time interval associated with the context resource |
| `http://hl7.org/fhir/CodeSystem/iana-link-relations` | `intervalDisjoint` | refers to a resource associated with a time interval that begins after the end of the time interval associated with the context resource, or ends before the beginning of the time interval associated with the context resource |
| `http://hl7.org/fhir/CodeSystem/iana-link-relations` | `intervalDuring` | refers to a resource associated with a time interval that begins before the beginning of the time interval associated with the context resource, and ends after the end of the time interval associated with the context resource |
| `http://hl7.org/fhir/CodeSystem/iana-link-relations` | `intervalEquals` | refers to a resource associated with a time interval whose beginning coincides with the beginning of the time interval associated with the context resource, and whose end coincides with the end of the time interval associated with the context resource |
| `http://hl7.org/fhir/CodeSystem/iana-link-relations` | `intervalFinishedBy` | refers to a resource associated with a time interval that begins after the beginning of the time interval associated with the context resource, and whose end coincides with the end of the time interval associated with the context resource |
| `http://hl7.org/fhir/CodeSystem/iana-link-relations` | `intervalFinishes` | refers to a resource associated with a time interval that begins before the beginning of the time interval associated with the context resource, and whose end coincides with the end of the time interval associated with the context resource |
| `http://hl7.org/fhir/CodeSystem/iana-link-relations` | `intervalIn` | refers to a resource associated with a time interval that begins before or is coincident with the beginning of the time interval associated with the context resource, and ends after or is coincident with the end of the time interval associated with the context resource |
| `http://hl7.org/fhir/CodeSystem/iana-link-relations` | `intervalMeets` | refers to a resource associated with a time interval whose beginning coincides with the end of the time interval associated with the context resource |
| `http://hl7.org/fhir/CodeSystem/iana-link-relations` | `intervalMetBy` | refers to a resource associated with a time interval whose end coincides with the beginning of the time interval associated with the context resource |
| `http://hl7.org/fhir/CodeSystem/iana-link-relations` | `intervalOverlappedBy` | refers to a resource associated with a time interval that begins before the beginning of the time interval associated with the context resource, and ends after the beginning of the time interval associated with the context resource |
| `http://hl7.org/fhir/CodeSystem/iana-link-relations` | `intervalOverlaps` | refers to a resource associated with a time interval that begins before the end of the time interval associated with the context resource, and ends after the end of the time interval associated with the context resource |
| `http://hl7.org/fhir/CodeSystem/iana-link-relations` | `intervalStartedBy` | refers to a resource associated with a time interval whose beginning coincides with the beginning of the time interval associated with the context resource, and ends before the end of the time interval associated with the context resource |
| `http://hl7.org/fhir/CodeSystem/iana-link-relations` | `intervalStarts` | refers to a resource associated with a time interval whose beginning coincides with the beginning of the time interval associated with the context resource, and ends after the end of the time interval associated with the context resource |
| `http://hl7.org/fhir/CodeSystem/iana-link-relations` | `item` | The target IRI points to a resource that is a member of the collection represented by the context IRI. |
| `http://hl7.org/fhir/CodeSystem/iana-link-relations` | `last` | An IRI that refers to the furthest following resource<br/>      in a series of resources. |
| `http://hl7.org/fhir/CodeSystem/iana-link-relations` | `latest-version` | Points to a resource containing the latest (e.g.,<br/>      current) version of the context. |
| `http://hl7.org/fhir/CodeSystem/iana-link-relations` | `license` | Refers to a license associated with this context. |
| `http://hl7.org/fhir/CodeSystem/iana-link-relations` | `linkset` | The link target of a link with the "linkset" relation<br/>      type provides a set of links, including links in which the link<br/>      context of the link participates.<br/>     |
| `http://hl7.org/fhir/CodeSystem/iana-link-relations` | `lrdd` | Refers to further information about the link's context,<br/>      expressed as a LRDD ("Link-based Resource Descriptor Document")<br/>      resource.  See  for information about<br/>      processing this relation type in host-meta documents. When used<br/>      elsewhere, it refers to additional links and other metadata.<br/>      Multiple instances indicate additional LRDD resources. LRDD<br/>      resources MUST have an "application/xrd+xml" representation, and<br/>      MAY have others. |
| `http://hl7.org/fhir/CodeSystem/iana-link-relations` | `manifest` | Links to a manifest file for the context. |
| `http://hl7.org/fhir/CodeSystem/iana-link-relations` | `mask-icon` | Refers to a mask that can be applied to the icon for the context. |
| `http://hl7.org/fhir/CodeSystem/iana-link-relations` | `media-feed` | Refers to a feed of personalised media recommendations relevant to the link context. |
| `http://hl7.org/fhir/CodeSystem/iana-link-relations` | `memento` | The Target IRI points to a Memento, a fixed resource that will not change state anymore. |
| `http://hl7.org/fhir/CodeSystem/iana-link-relations` | `micropub` | Links to the context's Micropub endpoint. |
| `http://hl7.org/fhir/CodeSystem/iana-link-relations` | `modulepreload` | Refers to a module that the user agent is to preemptively fetch and store for use in the current context. |
| `http://hl7.org/fhir/CodeSystem/iana-link-relations` | `monitor` | Refers to a resource that can be used to monitor changes in an HTTP resource.<br/>     |
| `http://hl7.org/fhir/CodeSystem/iana-link-relations` | `monitor-group` | Refers to a resource that can be used to monitor changes in a specified group of HTTP resources.<br/>     |
| `http://hl7.org/fhir/CodeSystem/iana-link-relations` | `next` | Indicates that the link's context is a part of a series, and<br/>      that the next in the series is the link target.<br/>     |
| `http://hl7.org/fhir/CodeSystem/iana-link-relations` | `next-archive` | Refers to the immediately following archive resource. |
| `http://hl7.org/fhir/CodeSystem/iana-link-relations` | `nofollow` | Indicates that the context’s original author or publisher does not endorse the link target. |
| `http://hl7.org/fhir/CodeSystem/iana-link-relations` | `noopener` | Indicates that any newly created top-level browsing context which results from following the link will not be an auxiliary browsing context. |
| `http://hl7.org/fhir/CodeSystem/iana-link-relations` | `noreferrer` | Indicates that no referrer information is to be leaked when following the link. |
| `http://hl7.org/fhir/CodeSystem/iana-link-relations` | `opener` | Indicates that any newly created top-level browsing context which results from following the link will be an auxiliary browsing context. |
| `http://hl7.org/fhir/CodeSystem/iana-link-relations` | `openid2.local_id` | Refers to an OpenID Authentication server on which the context relies for an assertion that the end user controls an Identifier. |
| `http://hl7.org/fhir/CodeSystem/iana-link-relations` | `openid2.provider` | Refers to a resource which accepts OpenID Authentication protocol messages for the context. |
| `http://hl7.org/fhir/CodeSystem/iana-link-relations` | `original` | The Target IRI points to an Original Resource. |
| `http://hl7.org/fhir/CodeSystem/iana-link-relations` | `payment` | Indicates a resource where payment is accepted. |
| `http://hl7.org/fhir/CodeSystem/iana-link-relations` | `pingback` | Gives the address of the pingback resource for the link context. |
| `http://hl7.org/fhir/CodeSystem/iana-link-relations` | `preconnect` | Used to indicate an origin that will be used to fetch required <br/>      resources for the link context. Initiating an early connection, which <br/>      includes the DNS lookup, TCP handshake, and optional TLS negotiation, <br/>      allows the user agent to mask the high latency costs of establishing a <br/>      connection. |
| `http://hl7.org/fhir/CodeSystem/iana-link-relations` | `predecessor-version` | Points to a resource containing the predecessor<br/>      version in the version history.<br/>     |
| `http://hl7.org/fhir/CodeSystem/iana-link-relations` | `prefetch` | The prefetch link relation type is used to identify a resource <br/>      that might be required by the next navigation from the link context, and <br/>      that the user agent ought to fetch, such that the user agent can deliver a <br/>      faster response once the resource is requested in the future. |
| `http://hl7.org/fhir/CodeSystem/iana-link-relations` | `preload` | Refers to a resource that should be loaded early in the <br/>      processing of the link's context, without blocking rendering. |
| `http://hl7.org/fhir/CodeSystem/iana-link-relations` | `prerender` | Used to identify a resource that might be required by the next <br/>      navigation from the link context, and that the user agent ought to fetch <br/>      and execute, such that the user agent can deliver a faster response once <br/>      the resource is requested in the future. |
| `http://hl7.org/fhir/CodeSystem/iana-link-relations` | `prev` | Indicates that the link's context is a part of a series, and<br/>      that the previous in the series is the link target.<br/>     |
| `http://hl7.org/fhir/CodeSystem/iana-link-relations` | `prev-archive` | Refers to the immediately preceding archive resource. |
| `http://hl7.org/fhir/CodeSystem/iana-link-relations` | `preview` | Refers to a resource that provides a preview of the link's context. |
| `http://hl7.org/fhir/CodeSystem/iana-link-relations` | `previous` | Refers to the previous resource in an ordered series<br/>      of resources.  Synonym for "prev". |
| `http://hl7.org/fhir/CodeSystem/iana-link-relations` | `privacy-policy` | Refers to a privacy policy associated with the link's context. |
| `http://hl7.org/fhir/CodeSystem/iana-link-relations` | `profile` | Identifying that a resource representation conforms<br/>to a certain profile, without affecting the non-profile semantics<br/>of the resource representation. |
| `http://hl7.org/fhir/CodeSystem/iana-link-relations` | `publication` | Links to a publication manifest. A manifest represents <br/>      structured information about a publication, such as informative metadata, <br/>      a list of resources, and a default reading order. |
| `http://hl7.org/fhir/CodeSystem/iana-link-relations` | `related` | Identifies a related resource. |
| `http://hl7.org/fhir/CodeSystem/iana-link-relations` | `replies` | Identifies a resource that is a reply to the context<br/>      of the link.<br/>     |
| `http://hl7.org/fhir/CodeSystem/iana-link-relations` | `restconf` | Identifies the root of RESTCONF API as configured on this HTTP server.<br/>      The "restconf" relation defines the root of the API defined in RFC8040.<br/>      Subsequent revisions of RESTCONF will use alternate relation values to support <br/>      protocol versioning. |
| `http://hl7.org/fhir/CodeSystem/iana-link-relations` | `ruleinput` | The resource identified by the link target provides an input value to an <br/>    instance of a rule, where the resource which represents the rule instance is <br/>    identified by the link context.<br/>     |
| `http://hl7.org/fhir/CodeSystem/iana-link-relations` | `search` | Refers to a resource that can be used to search through<br/>      the link's context and related resources. |
| `http://hl7.org/fhir/CodeSystem/iana-link-relations` | `section` | Refers to a section in a collection of resources. |
| `http://hl7.org/fhir/CodeSystem/iana-link-relations` | `self` | Conveys an identifier for the link's context.<br/>     |
| `http://hl7.org/fhir/CodeSystem/iana-link-relations` | `service` | Indicates a URI that can be used to retrieve a<br/>      service document. |
| `http://hl7.org/fhir/CodeSystem/iana-link-relations` | `service-desc` | Identifies service description for the context that<br/>      is primarily intended for consumption by machines. |
| `http://hl7.org/fhir/CodeSystem/iana-link-relations` | `service-doc` | Identifies service documentation for the context that<br/>      is primarily intended for human consumption. |
| `http://hl7.org/fhir/CodeSystem/iana-link-relations` | `service-meta` | Identifies general metadata for the context that is<br/>      primarily intended for consumption by machines. |
| `http://hl7.org/fhir/CodeSystem/iana-link-relations` | `sponsored` | Refers to a resource that is within a context that is <br/>		sponsored (such as advertising or another compensation agreement). |
| `http://hl7.org/fhir/CodeSystem/iana-link-relations` | `start` | Refers to the first resource in a collection of<br/>      resources. |
| `http://hl7.org/fhir/CodeSystem/iana-link-relations` | `status` | Identifies a resource that represents the context's<br/>      status. |
| `http://hl7.org/fhir/CodeSystem/iana-link-relations` | `stylesheet` | Refers to a stylesheet. |
| `http://hl7.org/fhir/CodeSystem/iana-link-relations` | `subsection` | Refers to a resource serving as a subsection in a<br/>      collection of resources. |
| `http://hl7.org/fhir/CodeSystem/iana-link-relations` | `successor-version` | Points to a resource containing the successor version<br/>      in the version history.<br/>     |
| `http://hl7.org/fhir/CodeSystem/iana-link-relations` | `sunset` | Identifies a resource that provides information about<br/>      the context's retirement policy.<br/>     |
| `http://hl7.org/fhir/CodeSystem/iana-link-relations` | `tag` | Gives a tag (identified by the given address) that applies to<br/>      the current document.<br/>     |
| `http://hl7.org/fhir/CodeSystem/iana-link-relations` | `terms-of-service` | Refers to the terms of service associated with the link's context. |
| `http://hl7.org/fhir/CodeSystem/iana-link-relations` | `timegate` | The Target IRI points to a TimeGate for an Original Resource. |
| `http://hl7.org/fhir/CodeSystem/iana-link-relations` | `timemap` | The Target IRI points to a TimeMap for an Original Resource. |
| `http://hl7.org/fhir/CodeSystem/iana-link-relations` | `type` | Refers to a resource identifying the abstract semantic type of which the link's context is considered to be an instance. |
| `http://hl7.org/fhir/CodeSystem/iana-link-relations` | `ugc` | Refers to a resource that is within a context that is User Generated Content.<br/>     |
| `http://hl7.org/fhir/CodeSystem/iana-link-relations` | `up` | Refers to a parent document in a hierarchy of<br/>      documents.<br/>     |
| `http://hl7.org/fhir/CodeSystem/iana-link-relations` | `version-history` | Points to a resource containing the version history<br/>      for the context.<br/>     |
| `http://hl7.org/fhir/CodeSystem/iana-link-relations` | `via` | Identifies a resource that is the source of the<br/>      information in the link's context.<br/>     |
| `http://hl7.org/fhir/CodeSystem/iana-link-relations` | `webmention` | Identifies a target URI that supports the Webmention protocol.<br/>    This allows clients that mention a resource in some form of publishing process<br/>    to contact that endpoint and inform it that this resource has been mentioned. |
| `http://hl7.org/fhir/CodeSystem/iana-link-relations` | `working-copy` | Points to a working copy for this resource. |
| `http://hl7.org/fhir/CodeSystem/iana-link-relations` | `working-copy-of` | Points to the versioned resource from which this<br/>      working copy was obtained.<br/>     |
