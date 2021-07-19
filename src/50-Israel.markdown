# Israel

*Eli Greenbaum[^israel_bio]*

## Introduction to software protection under Israeli law

### Body of law

The Israeli Copyright Law of 2007 (the “Copyright Law”) modernized the
protection of intellectual property in Israel. The Copyright Law
replaced the prior outdated statutory framework, which consisted of both
the Copyright Ordinance of 1924 and the British Copyright Act of 1911,
the latter having been made applicable to the British Mandate in 1924
and adopted by the nascent State of Israel in 1948.[^israel_1] The Copyright
Law expressly provides for the copyright protection of computer
programs.

A full analysis of the patent license provisions incorporated in many
free and open source software (“FOSS”) licenses is beyond the scope of
this chapter. However, it should be noted that it is possible, in
certain circumstances, to protect software under Israeli patent law. On
March 15, 2012, the Israeli Patent Authority issued new guidelines
regarding the patentability of software inventions in Israel. The new
guidelines adopt a relatively liberal approach regarding the patent
eligibility of software inventions.

### Copyright Act: Object of protection

The Copyright Law expressly provides that computer programs, which are
categorized as literary works, constitute copyrightable subject matter.
The Copyright Law also provides that a computer program includes the
program “in any form that it may be expressed”. This provision is
intended to be consistent with the definition of computer programs in
Article 4 of the WIPO Copyright Treaty.[^israel_2]

### Authors/Copyright owners

Section 34 of the Copyright Law provides that, absent an agreement to
the contrary, an employer shall be the owner of the copyright of a work
that was created by an employee “for the purpose and in the course” of
such employee’s work. As there may be circumstances where it is not
clear whether an employment relationship exists, or whether the work was
created “for the purpose and in the course of” employment within the
meaning of the statute, employment agreements in Israel frequently
contain express provisions to clarify the ownership of created works, as
well as affirmative assignments of rights. The Copyright Law takes a
different tack with respect to works for hire. Section 35(a) of the
Copyright Law provides that in the absence of an "express or implied
agreement" to the contrary, the default rule is that the creator of a
work, and not the party that commissioned the work, will be the original
owner of the copyright in a commissioned work. However, as that
provision allows an "implied" agreement to determine copyright
ownership, the default rule is less than clear. As such, it is
recommended that consulting agreements or other “work for hire”
arrangements in Israel include an express grant of the copyright to the
commissioning entity, if that is the intention of the parties.

### Compilations

The Copyright Law also protects compilations as literary works. Section
4(b) of the Copyright Law provides that the original expression
protected in a compilation is the originality of selection or
arrangement of individual works or material in the compilation.

### Joint works

The Copyright Law recognizes the possibility of joint works but does not
expressly provide for the manner in which joint owners in a copyright
may exploit the work. Case law has not provided a clear determination of
whether Israeli law should generally follow the rule in the United
Kingdom — such that the consent of all joint owners would be required to
license a work — or whether it should generally follow the rule in the
United States — such that each joint owner should be able to license the
work without consent of the other joint owners, subject to a duty of
accounting.[^israel_3] As such, the right of joint owners to exploit a
jointly-owned work, including the right to grant licenses to third
parties or to individually enforce the copyright, is at present unclear
under Israeli law.

Section 54(b) of the Copyright Law requires that a plaintiff in a
copyright infringement suit join all other right holders in the suit.
This would seem to require that all joint owners of a copyright be
joined in any action to enforce a copyright.

### Derivative works

Section 16 of the Copyright Law defines a “derivative work” as an
original work that is “materially based” on another work. While not
expressly set forth in the statute, the copyright of the author of the
derivative work should extend only to the original elements of the
derivative work, while the rights of the copyright holder of the
original work should remain intact.[^israel_4] As noted below, subject to
certain statutory exceptions, the right to create a derivative work is
one of the exclusive economic rights included in a copyright.

The question of what constitutes a “derivative work” is, of course, of
primary importance in the interpretation of the GPL, which (in very
brief summary) may potentially require the disclosure of the source code
of works that are derivative of the licensed work. To the extent the
statutory definition of a “derivative work” impacts the answer to that
question,[^israel_5] it should be noted that the statutory test of the
Copyright Law looks to the “materiality” of the “use” that the
subsequent work makes of the protected work. This test may subtly differ
from the definition of a “derivative work” in other jurisdictions that
look to the substance of the protected work that is incorporated in the
potentially derivative work, rather than how the potentially derivative
work uses that material.

### Exclusive rights

Section 11 of the Copyright Law sets forth the exclusive economic rights
afforded under a copyright. All of the rights apply in the case of a
computer program. The rights include:

(a) The right to copy the work;

(b) The right to publish the work, if the work has not yet been
published;

(c) The right to publicly perform the work;

(d) The right to broadcast the work;

(e) The right to make the work available to the public;

(f) The right to create and a exploit derivative works; and

(g) The right to lease the work.

Several other provisions of the Copyright Law are relevant to the
interpretation of these enumerated exclusive rights in the context of
computer programs. Section 12 of the Copyright Law provides that
technological and electronic storage of a work, as well as “temporary”
copying of a work, will also be deemed copying for purposes of the law.
These provisions bear on the possibility of infringing a copyright by
running a computer program or by accessing data over the internet.
However, Section 26 of the Copyright Law limits the exclusive right of
“temporary” copying to certain purposes and to the extent the copy
itself has significant economic value.

In addition, section 11(7) of the Copyright Law expressly provides that
the “right to lease the work” applies to computer programs. Section 17
of the Copyright Law limits this right to the lease of physical copies
of the work for commercial purposes, and provides that the right does
not include the exclusive right to lease computer programs or recordings
that are inseparable from the item that is the primary object of the
lease. As such, the exclusive right to lease a copy of a computer
program is not infringed by the lease of consumer goods that include
software.[^israel_6]

### Exceptions to exclusive rights

The Copyright Law provides for certain “permitted uses” which constitute
exclusions to the exclusive rights of copyright holder enumerated above.
These include, as described in more detail below, the right to create
copies or derivative works of computer programs for the purpose of
backups, maintenance and support, fixing bugs, and ensuring
interoperability.[^israel_7] These “permitted uses” may be exercised only by
the holder of a “lawful copy” of the program or on her behalf.

Section 24(a) of the Copyright Law provides for a right to create backup
copies. It states that that the holder of a lawful copy of a computer
program may create additional copies of such program for backup
purposes. Such copies, however, must be destroyed once the need for them
passes.

Section 24(b) of the Copyright Law provides that that the holder of a
lawful copy of a computer program may copy such program, either for the
purpose of maintenance of such program or for the purpose of maintenance
of a computer system, if such maintenance is required to use such
program. Such use is also permitted for the purpose of providing such
maintenance to the holder of a lawful copy.

Section 24(c) of the Copyright Law allows for creating both copies and
derivative works of computer programs for the purpose of fixing bugs,
interoperability and information security. Without repeating verbatim
the detailed conditions set forth in this section, it should be noted
that this section is broadly intended to allow reverse engineering and
decompilation of computer programs for the enumerated purposes.[^israel_8] It
is not clear whether a licensee may contractually agree to forgo the
rights of “permitted uses” set forth in this section. As such, the
enforceability of common contractual terms against reverse engineering
is at present unclear under Israeli law.

### Moral rights

Section 45(a) of the Copyright Law expressly provides that moral rights
do not exist in computer programs.

### Terms of protection

The term of protection for computer programs is the same as for other
works. Section 38 of the Copyright Law provides that copyright
protection in a work is for the life of the author plus 70 years,
regardless of whether the author owns the copyright. Section 39 of the
Copyright Law provides that in a joint work, the term of copyright
protection is for 70 years following the death of the last joint author.
However, the term of protection for works that were originally published
in a country outside of Israel is generally limited to the term of
protection afforded by that country.

### Copyright assignment

Except in the context of the employer-employee relationship, the
transfer of a copyright (or the exclusive license in respect thereof)
requires a written assignment. In contrast to the prior law, the
Copyright Law does not require that such writing be signed by the
parties, which raises the possibility that unsigned messages (such as
emails) may be sufficient to effect an assignment of a copyright.

### Enforcement

The Copyright Law sets forth both civil and criminal penalties for the
infringement of copyrights. Civil penalties, as described in more detail
below under the heading “Legal Remedies”, can include claims for an
accounting of profits, actual damages or statutory damages. Criminal
sanctions can include imprisonment and the imposition of a statutory
fine, and generally can be imposed for infringement for the purpose of
commerce, or the sale, lease or distribution of infringing work in
commerce.

The Copyright Law also imposes a special duty on the office holders in a
corporation. Section 63 of the Copyright Law provides that office
holders must supervise employees in order to ensure that such employees
do not commit acts of infringement. Section 63(b) of the Copyright Law
sets forth a presumption that an office holder has not fulfilled his
statutory duty of supervision if any such acts of infringement are
committed. Statutory fines can be imposed on such office holders that do
not satisfy their duty of supervision.

### Technical devices and effective technological measures

The Copyright Law does not contain provisions regarding the
circumvention of technological measures implementing digital rights
management. This reflects the deliberate decision of the Israeli
parliament (the Knesset) not to include such provisions in the law. In
5097/11 Telran Communications (1986) Ltd. v Charlton Ltd., the Supreme
Court confirmed that the Copyright Law should not be interpreted as
prohibiting the circumvention of technological measures implementing
digital rights management.

It is possible, however, that the circumvention of effective
technological measures may present a criminal violation of the Computer
Law of 1995 (the “Computer Law”). Sections 2 and 7 of the Computer Law
prohibit the unauthorized disruption of the proper operation of a
computer system, or the unauthorized erasure, change or disruption of
material on the computer system. It is unclear whether the circumvention
of effective technological measures falls within the ambit of these
provisions, especially considering the Knesset’s deliberate decision not
to include express provisions regarding this issue in the Copyright Law.

## Analysis of FOSS under Israeli law

Under Israeli law, rights in FOSS do not differ from other forms of
copyright and patent licensing. FOSS is protected under the Copyright
Law as with any other form of software, and there is no reason to
believe that FOSS licenses would not constitute enforceable legal
contracts. As such, a breach of a FOSS license would be viewed as a
breach of a contract, and the use of FOSS in breach of a license is
likely to constitute copyright infringement.

For example, recently the Jerusalem District Court in TA 3560/09 and TA
3561/09, Reuveni v. Mapa Publishing, Ltd. enforced the terms of the
Creative Common BY-NC-ND license against a commercial defendant. The
plaintiffs, amateur photographers, had uploaded photographs to the
Internet pursuant to that license. The defendant, a commercial
publisher, published the pictures both in a book for commercial sale as
well as on its website, violating the terms of the Creative Commons
license. The Court found that, in violating the license, the defendant
had infringed the plaintiffs' copyright and ordered the defendant to pay
monetary damages. The case presents an important precedent which shows
that Israeli courts are willing to enforce the terms of open source
licenses against commercial defendants. Several questions raised by the
decision, including the issues of the contractual validity of a FOSS
licenses and how damages should be calculated in an action for
infringement of FOSS, are discussed in more detail below.

### Rights of the original co-authors

FOSS is often developed within a collaborative development model. As
noted above, while the Copyright Law recognizes the possibility of joint
authors, it does not specifically set out the rights afforded to each of
the joint owners. This increases the importance under Israeli law of
ensuring that contributors to open source projects have executed
contribution agreements, in which they either assign or license their
contributed code to such project.

### Authors of modifications

Successive versions of FOSS may build upon the works of previous FOSS
authors. As in many other legal systems, Israeli law recognizes the
copyright of successive authors in the derivative work. This copyright
in the derivative work should be subject to the copyright of the
original author to the original work.

### Validity of FOSS licenses

The Contract Law of 1973 (the “Contract Law”) provides that under
Israeli law contracts are formed through a process of offer and
acceptance. The statute details how this requirement of offer and
acceptance can be satisfied. In addition, case law has generally
emphasized the substance of contract law rather than the form and, as
such, Israeli law puts a strong emphasis on questions of good faith and
fair dealing between the parties.[^israel_9]

Commercial license agreements generally satisfy the statutory
requirements of contract formation, in that they are often reached
through express acceptance of the terms of the license following a
process of negotiation. FOSS licenses that are reached through this
standard process of offer and acceptance should also be seen as validly
formed and should be enforced as regular contracts. In practice,
however, the acceptance of a FOSS license will frequently not involve
such a process of offer and acceptance.[^israel_10] Often a FOSS license does
not provide for an express agreement between the parties, but merely
sets forth conditions that a licensee is required to satisfy in order to
benefit from the protection of the license.[^israel_11] For example, FOSS code
is often made available through the Internet with the minimal statement
that it is being made available pursuant to a specific FOSS license.
Even so, Israeli contract law is likely to recognize FOSS licenses as
validly formed legal contracts. First, Section 6 of the Contract Law
expressly recognizes that contracts may be accepted through a manner of
conduct. In addition, the Standardized Contract Law of 1982 (the
“Standardized Contract Law”) generally recognizes the contractual
validity of “standardized contracts” that may be either accepted or
rejected by a counterparty.[^israel_12] This conclusion is likely to be
bolstered by the general emphasis of Israeli law with regard to good
faith and fair dealing, since the FOSS license will be the only grant of
permission to use the FOSS work.[^israel_13]

The plaintiffs in Reuveni (the case referenced above) did seem to
advance contractual claims when they asserted that the defendants did
not satisfy the conditions set forth in the Creative Commons
license.[^israel_14] The court, however, did not consider the question of
whether the Creative Commons constituted an enforceable legal contract
and proceeded directly to the issues of copyright infringement and
damages. As such, the Reuveni decision leaves open the question of
whether FOSS licenses constitute enforceable legal contracts.

The Contract Law does not incorporate a requirement of consideration. As
such, questions that may arise in other jurisdictions regarding the
consideration received by the licensor in a FOSS context do not arise
under Israeli law.

### Termination

As noted above, Israeli law generally interprets licenses according to
the standard rules of contract law. As such, a license that does not
contain an express term may be terminated by the licensor by providing
reasonable prior notice. What constitutes “reasonable” prior notice
varies on a case-by-case basis according to the circumstances, and is
ultimately a question determined by the court. FOSS licenses do not
generally contain an express term and are generally granted for an
indefinite period of time. As such, Israeli law presents the risk that a
FOSS licensor can terminate a FOSS license upon reasonable notice.[^israel_15]

### Waiver and liability

FOSS licenses typically contain strong disclaimers of warranties and
liability. The enforceability of such broad disclaimers under Israeli
statutory law is not entirely clear, and the case law has not yet
considered the application of broad disclaimers in the software
licensing context. However, it is important to note under Israeli law
that such disclaimers may be entirely reasonable for FOSS that is made
freely available without charge, especially considering that the author
of such works may not have any control over the actual distribution or
use of her work.

Israeli law provides for certain implied warranties in the context of a
sale of goods, services or rights, including with regard to rights in
intellectual property.[^israel_16] For example, Section 11(3) of the Sale Law
of 1968 (the “Sale Law”) generally provides for implied warranties of
“regular or commercial use or any other special purpose that may be
implied by agreement”. These implied contract terms are similar but not
equivalent to the implied warranties of merchantability and fitness for
a particular purpose provided by the Uniform Commercial Code.
Additionally, Section 18(a) of the Sale Law provides for an implied
warranty of non-infringement. These provisions of the Sale Law predate
the significant development of the Israeli high-tech industry and do not
seem to have been directed towards the problems raised by intellectual
property licenses generally and software licenses in particular. In
addition, Israeli case law regarding the application of these statutory
provisions to intellectual property is sparse.

The ability of contracting parties to entirely disclaim such implied
warranties is not entirely clear. Section 4(b) of the Sale Law provides
that warranties will be implied only in the absence of any agreement to
the contrary between the parties. At the same time, however, the
Standardized Contract Law provides that a court may ignore or change
unconscionable terms in a “standardized contract”, and Section 4(1) of
that statute provides for a presumption that contractual terms limiting
liability in a “standardized contract” will be deemed unconscionable.
FOSS licenses, in that they are typically drafted in advance by the
licensor for an indefinite number of licensees who are not able to
negotiate the terms of the license, facially fit the statutory
definition of a “standardized contract.” As noted above, however, broad
disclaimers of liability and warranty may be entirely appropriate in the
FOSS context. The enforceability of such disclaimers in the software
licensing context in general and for FOSS licenses in particular has not
yet been examined by Israeli case law.

Licensors should note that Section 16 of the Sale Law provides that the
implied warranties of merchantability and fitness for a particular
purpose may not be disclaimed if the non-conformity results from facts
that the seller “knows or has reason to know of”. While not explicit in
the statute, this provision may also apply to the implied warranty of
non-infringement.[^israel_17] Again, the application of these provisions to the
licensing of intellectual property has not been satisfactorily explored
in Israeli case law.

## Remedies

### Copyright infringement — damages

Under Israeli law, a copyright holder may be entitled to either an
accounting of profits or damages (whether actual or statutory) for the
infringement of a copyright.[^israel_18] Criminal penalties may also be
generally imposed with regard to infringements of copyright in commerce,
but a full discussion of such criminal penalties is beyond the scope of
this article.

In an accounting of profits, the plaintiff is entitled to receive the
profits obtained as a result of the infringement of the copyrighted
work. Often only a part of the defendant’s work is based on the
infringed work, and in such event a court must determine what proportion
of profits should be allocated to the infringed work. Though the
question has not yet been addressed by case law, it seems that an
infringer of software (including FOSS) should similarly be entitled to
an accounting of profits of the infringing party.[^israel_19]

Actual damages may be difficult to assess in a suit for FOSS
infringement, especially where the work is generally made available free
of charge. In addition to actual damages, however, the Copyright Law
also provides for the possibility of statutory damages in the amount of
up to 100,000 New Israeli Shekels for each instance of infringement,
without any requirement to prove actual damages. A court generally has
wide latitude in setting the amount of statutory damages. Section 56(b)
of the Copyright Law sets out factors that for the court to consider in
this regard. Factors applicable to the infringement of FOSS may include
the damage caused to the copyright holder, the profits of the infringing
party and whether the infringing party acted in good faith.

FOSS copyright owners may find claims for statutory damages easier to
assert than attempting to prove actual damages. The plaintiffs in
Reuveni, for example, asserted a successful claim for statutory damages.
At the same time, the court in Reuveni, in setting the amount of
statutory damages, also took into account the fact that the plaintiffs
were amateur hobbyists who did not expect to profit from the copyrighted
works and who, in fact, did not suffer material economic damage from the
infringement. In light of these factors, the court awarded the
plaintiffs substantially less than the 100,000 NIS ceiling per
infringement. The court distinguished the facts in Reuveni from another
case where the infringed work was the well-known photo of a professional
photographer and where the court had awarded substantially higher
statutory damages per infringement. While FOSS copyright holders are
often professional programmers or engineers, FOSS is often provided free
of charge by the copyright holder with little or no expectation of
economic gain. As such, the factors enumerated in Reuveni may prove
relevant to the calculation of statutory damages in future FOSS
infringement actions.

Section 60(c) of the Copyright Law may restrict the remedies available
against a licensee in good faith of intellectual property. While Section
60 of the Copyright law sets forth certain actions that a court may
order in respect of an infringing work, Section 60(c) subjects these
provisions to the “market overt rule” set forth in Section 34 of the
Sale Law. Subject to the conditions of the statute, the “market overt
rule” provides that the purchaser of an item in good faith obtains good
title regardless of whether the vendor itself can pass on good title. As
such, an owner of intellectual property may be restricted in his ability
to file suit against the end users of pirated or infringing intellectual
property, and may only be able to file suit against the providers such
infringing works.

### Contract remedies — injunction

Section 53 of the Copyright Law provides that the holder of a copyright
is entitled to obtain an injunction against an infringer, “unless the
court determines that justifications exist for denying such an
injunction.” Israeli courts may also grant temporary injunctions against
infringers. [^israel_20] The grant of an injunction may prove of central
importance to the licensor of open source software, especially given the
difficulty of proving actual damages. The plaintiffs in Reuveni had
dropped their demand for an injunction, and the court in that case
opined that the course of events would have in any event mooted such a
demand. Nonetheless, the court seemed to state that it would have been
prepared to consider such a demand had it been raised by the plaintiffs.

### Contract remedies — specific performance

In addition to an infringement claim, copyright holders may also bring
an action for breach of contract. Specific performance is a remedy
theoretically available under Israeli law for the breach of contract.
Section 3 of the Contract Law (Remedies for Breach) of 1970 expressly
provides for the availability of this remedy to the non-breaching party,
and a long tradition of Israeli case law has emphasized the importance
of specific performance as a remedy for breach of contract.[^israel_21] This
approach contrasts strongly with the common law tradition of favoring an
award of monetary damages rather than specific performance of the
contract.

As such, to the extent contractual remedies are available for breach of
an open-source license, licensees may find themselves exposed to the
possibility of orders for specific performance. Such orders could
include, for example under the terms of the GPL, an injunction to
release the source code of the licensee’s work. Licensees that have
discounted the possibility of such injunctions under the rules of other
legal systems should be aware of this possibility under Israeli law.

[^israel_bio]: *Eli Greenbaum is an attorney at Yigal Arnon & Co. in Jerusalem, specialising in
intellectual property law and transactions. He has an M.S. in Applied
Physics from Columbia University and a J.D. from Yale Law School. Eli
has published widely in the areas of open source software and
open hardware. 
<http://www.arnon.co.il>*


[^israel_1]: The Copyright Act of 1911 and the Copyright Ordinance of 1924
    continue in certain circumstances to apply to works and acts of
    infringement that predate the Copyright Law.

[^israel_2]: Israel is a signatory to the WIPO Copyright Treaty, but has yet to
    ratify the treaty or introduce implementing legislation. Several
    provisions of the WCT, however, have been implemented in the
    Copyright Law. Other provisions, such as the requirement of
    contracting states to provide for legal remedies against the
    circumvention of effective technological measures, have not yet been
    adopted into Israeli law. See below under the heading “Technical
    Devices and Effective Technological Measures”.

[^israel_3]: See paragraphs 15-16 of the dissenting opinion of Justice Englard
    in IE 1567/99 Sivan v. Shefer, discussing the English and American
    approaches and their application to Israeli law. See also IE 5365/11
    AKUM Ltd. v EMI Music Publishing Ltd. (suggesting, but not holding,
    that the proper intepretation of the rights of joint owners under
    Israeli copyright law should be determined by reference to Section
    31(A)(1) of the Real Property Law, which provides that joint owners
    in property can each make reasonable use of the property without the
    permission of the other owners, as long as that use does not
    interfere with the rights of other owners.)

[^israel_4]: TONY GREENMAN, ZEHUYOT YOZRIM, “Copyright”, 2nd ed. 2008
    (hereinafter GREENMAN), at 212.

[^israel_5]: This article does not address the question of whether the GPL may
    potentially reach beyond the statutory definition of a “derivative
    work”. The answer to that question depends on the contractual
    validity and interpretation of the GPL.

[^israel_6]: 1 GREENMAN, at 265.

[^israel_7]: The Copyright Law enumerates other “permitted uses” which are not
    applicable or not specific to computer programs, including the
    doctrine of “fair use”. These “permitted uses” are beyond the scope
    of this chapter.

[^israel_8]: See the Proposed Copyright Law, 196 Reshumot 1116 (July 20, 2005),
    at 1127.

[^israel_9]: See, e.g., Sections 12 (requiring parties to act in good faith in
    contractual negotiations), and 39 (requiring good faith in
    satisfying contractual terms and obligations) of the Contract Law of
    1973.

[^israel_10]: The Free Software Foundation has taken the position that the GPL
    is a license but not a contract. See
    <http://www.gnu.org/philosophy/enforcing-gpl.html>. This position
    seems to be motivated by an attempt to circumvent the legal
    requirements of contract formation, such as the elements of offer
    and assent. However, many commentators have asserted that this
    position is not an accurate description of the law. See HEATHER J.
    MEEKER, THE OPEN SOURCE ALTERNATIVE (2008) at 225. In addition, it
    is unclear under Israeli law whether a license cannot be a contract.
    See generally 2 GREENMAN, at 555 (describing a license as a
    contract) and 568 (describing the GPL and open source licenses as
    enforceable legal contracts). The question of whether the GPL is a
    contract or license may take on more signifigance in Israel, where
    specific performance can be available as remedy for breach of
    contract. This is discussed is more detail below in the context of
    contractual remedies for the breach of the GPL. In any event, the
    position taken by the Free Software Foundation need not be the
    stance of all licensors of FOSS, whether made available under the
    GPL or pursuant to other FOSS licenses.

[^israel_11]: This approach is cogently and succinctly expressed by section 5
    of version 2.1 of the GPL: “You are not required to accept this
    License, since you have not signed it. However, nothing else grants
    you permission to modify or distribute the Program or its derivative
    works. These actions are prohibited by law if you do not accept this
    License. Therefore, by modifying or distributing the Program (or any
    work based on the Program), you indicate your acceptance of this
    License to do so, and all its terms and conditions for copying,
    distributing or modifying the Program or works based on it.” See
    also Section 9 of version 3.0 of the GPL.

[^israel_12]: GABRIELA SHALEV, DINEI HOZIM, “Laws of Contracts” at 608 (1990)
    (hereinafter SHALEV). Together with this acceptance of “standardized
    contracts” as generally valid, Israeli law limits the efficacy of
    “unconscionable” terms in such contracts. See the discussion below
    under the heading “Waiver and Liability”.

[^israel_13]: See also 2 GREENMAN, at 568 (describing the GPL and open source
    licenses as enforceable legal contracts). Note that the question of
    whether a FOSS license is a contract or not should not affect the
    rights in bankruptcy. Section 123 of the Bankruptcy Ordinance -
    1980, which provides for the continued use of copyrights by a
    licensee in bankruptcy so long as royalties continue to be paid,
    does not distinguish between contractual or other rights in
    intellectual property.

[^israel_14]: As noted, the FOSS license is the only authorization a defendant
    may have to use the FOSS work. As such, defendants may have little
    incentive to challenge the validity of the license. The defendants
    in Reuveni, for example, did not attack the contractual validity of
    the Creative Commons license. This may not be true, however, with
    regard to FOSS licenses that impose affirmative obligations on
    licensees, such as the requirements of the GPL with regard to the
    disclosure of source code.

[^israel_15]: 2 GREENMAN, at 555.

[^israel_16]: See Section 4(a) of the Sale Law. See also EYAL ZAMIR, HOK
    HAMEHER, “The Sale Law of 1968” (1987) (hereinafter ZAMIR), at 138.

[^israel_17]: ZAMIR, at 379.

[^israel_18]: The remedies of actual damages and an accounting of profits are
    implied by the Copyright Law, though not expressly provided for
    therein. Section 52 of the Copyright Law provides that the
    infringement of a copyright is cause for a civil action for damages,
    and case law has held that plaintiffs are entitled to an accounting
    of profits or actual damages. See, e.g. , 23/81 Hershko v. Orbach
    (1988) and 241/55 Neographica Printing vs. Masada (1957). Actual
    damages, as used herein, includes possible damages for the “theft”
    of the copyright as well as indirect damages. A discussion of the
    method of calculation of actual damages for copyright infringement
    under Israeli law is beyond the scope of this article. Regarding the
    remedy of an accounting of profits, see 2 GREENMAN, at 790.

[^israel_19]: The questions raised by an accounting of profits did not come up
    in Reuveni, as the defendant in that case did not collect any actual
    profits from the sale of the infringing work. See Reuveni at pp.4.

[^israel_20]: Generally, in determining whether to grant a temporary
    injunction, a court will weigh the “balance of the hardships” – the
    damage to the plaintiff if the request for temporary relief is
    rejected against the damage to the plaintiff (or other parties) if
    the request is granted. Prior to the adoption of the Copyright Law
    in 2007, the Supreme Court opined that a temporary injunction for
    the infringement of copyright “should be granted immediately once
    the copyright holder has succeeded in proving that its rights have
    been infringed.” See RAA 67141/02 Akum Ltd. vs. Galie Tzahal (2003).
    Even so, the subsequently-adopted section 53 of the Copyright Law
    might be interpreted as granting courts more discretion in
    determining whether to award a temporary injunction.

[^israel_21]: See SHALEV, at 527, n. 1.

