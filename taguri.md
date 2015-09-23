# Tag URI

### Reference

* http://www.taguri.org/

### Purpose

The _tag_ algorithm lets people mint — create — identifiers that no one else using the same algorithm could ever mint. It is simple enough to do in your head, and the resulting identifiers can be easy to read, write, and remember. The identifiers conform to the [URI (URL) Syntax](http://www.ietf.org/rfc/rfc3986.txt).

### Status

2005-10-26: The 'tag' URI scheme has been published as [RFC 4151](http://www.faqs.org/rfcs/rfc4151.html).

To do:

*   **Compatibility with RFC 2822 email addresses:** there was [discussion](http://lists.w3.org/Archives/Public/uri/2005Oct/0008.html) on uri@w3.org about how to upgrade the tag scheme's syntax for better compatibility with RFC 2822 email addresses. This change didn't make it into the RFC.
*   **Internationalisation:** tags should exists in an IRI form, so that humans can easily mint them in their native languages. A [previous attempt](http://lists.w3.org/Archives/Public/uri/2004Oct/0013) at an IRI form ran into the mud.

### History

In early 2001, similar schemes were proposed independently by ([Sandro Hawke](http://www.w3.org/People/Sandro/), [The TANN URI Scheme](http://www.w3.org/2001/02/tann/)) and [Tim Kindberg](http://www.champignon.net) ([list email](http://web.archive.org/web/20030602090512/lists.netsol.com/cgi-bin/wa?A2=ind0101&L=urn-ietf&D=1&T=0&O=D&F=&S=&P=815) and [this draft](draft-2001-03-02.pdf)). We then collaborated to develop the current scheme, with feedback from various sources.

[Here](draftHistory.html) is a short and incomplete history of drafts prior to RFC publication.

### Tutorial

I (Sandro) have a dog named Taiko, which is a fairly obscure name, but I can't be sure he's the only dog on the planet with that name. I want to be able to talk about him using just his name (without reference to myself, the town I live in, etc) and I want to be sure people will not accidentally think I'm talking about some other dog also named Taiko. So I'm going to give him a tag URI.

Step 1\. Identify myself. I have two choices: I can use one of my e-mail addresses (sandro@hawke.org, sandro@w3.org, sandro@world.std.com) or I can use a domain name assigned to me (such as hawke.org). I could also use a shared domain name (w3.org) if I had explicit permission from the domain holder.

Step 2\. Pick a date. It's possible that in 100 years my great grandson Sandro Hawke IV will be using "sandro@hawke.org" for e-mail. He may even have a dog named Taiko, and I still want my tag to name my Taiko, not his. So I pick some date during which the address "sandro@hawke.org" was definitely mine. I'll pick yesterday, Tuesday, June 5, 2001\.

Step 3\. Encode the date as characters, using [ISO 8601](http://www.w3.org/TR/1998/NOTE-datetime-19980827): "2001-06-05". If I had picked the first day of a month, back in step 2, I would not include the day. If I had picked the first day of a year, I would not include the month or day.

Step 4\. Pick a unique name for the object. But it has to be unique only for the already-chosen identity and date. "Taiko" seems like a fine choice here. I don't want to use a name like "1", because then I'm much more likely to get confused and accidentally call my _other_ dog "1". I also want to avoid accidentally reusing a name, but by always using the previous day's date I essentially eliminate that risk: I only need to remember names for the rest of the day.

Step 5\. Combine them like this: **tag:sandro@hawke.org,2001-06-05:Taiko**.

### FAQ

<a name="whoIsUsing">

#### Who is using tags?

</a>

<a name="whoIsUsing">Tags are used to identify blog items in the</a> [Atom](http://www.atomenabled.org/) personal publishing standard, as in [this example](http://www.intertwingly.net/wiki/pie/IdElement?action=highlight&value=tag%3A).

Tags are also used in [YAML](http://www.yaml.org/) to [identify type information](http://yaml.org/spec/#model-tag).

Please let [Tim Kindberg](mailto:tim@matter2media.com) know of other uses.

#### What does a given tag denote?

That's undefined in the tag specification; you'd need to look at the particular protocol in which they are used. Tags constitute only a scheme for minting identifiers: there is no authoritative resolution mechanism.

#### Why not use an http URL instead?

Indeed, Sandro might instead have named his dog http://hawke.org/2001/06/05/Taiko.

There are different points of view about this. The main argument against tags is "Why invent a new URI scheme when an old one — http — could be used?" Some arguments in favour are:

*   "But that initial 'http' might be taken to imply the existence of a web resource that the minting entity doesn't necessarily want to provide — at least, not over HTTP."
*   "I don't have a domain but I have an email address and I want to identify some stuff."
*   "Tags are unique for all time by construction. But a domain name (in an http URL) has no long-term guarantees about unique use — it could be re-assigned to an independent party. I could rely on purl.org to guarantee uniqueness for me (or rather, for whatever names I can grab after purl.org/net); but why rely on anyone when I don't need to?"

#### When can I use a tag someone else minted? What if someone else uses a tag I minted?

This specification only tells people how to mint unique identifiers. Policies concerning the use of these identifiers should be set for each situation or protocol in which they are used.

#### Why restrict tags to utilise only domain names and email addresses?

We considered other identifiers assignable on a quantum of a day, such as telephone numbers and IP numbers. But it seemed better to keep things simple.

#### Are tags good XML Namespace Names?

There are two schools of thought about [XML namespace names](http://www.w3.org/TR/REC-xml-names/): (1) the name serves purely to distinguish otherwise-identical XML element names, and (2) the names leads to documentation, schema, and other information about the elements. For people firmly in the first camp, tags make good namespace names; for everyone else, working http URIs are recommended.

#### Are tags good RDF identifiers?

As with XML Namespaces, there are two schools of thought. Do you want the web's default mechanism at your disposal for fetching information about the identified thing? If so, then HTTP URIs are probably better used.

#### Do tags have anything to do with the W3C's TAG (Technical Architecture Group)?

No!

### This Site

This web site is maintained by [Tim Kindberg](http://champignon.net) and [Sandro Hawke](http://www.w3.org/People/Sandro/) as a place for authoritative information about the "tag" URI scheme. It is expected to stay small and simple.

_Last updated 2008-07-09._
