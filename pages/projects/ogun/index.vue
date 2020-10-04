<template>
  <div>
    <div>
      <div>
        <span class="orionAmber--text logo">OGUN</span>
      </div>
      <div>
        <span class="orionTeal--text logo-sub">Manufacturing ERP System</span>
      </div>
      <v-row justify="end" no-gutters>
        <v-col>
          <v-spacer />
          <v-menu rounded="lg" offset-y>
            <template v-slot:activator="{ attrs, on }">
              <v-btn
                class="z-depth-0 mb-2"
                v-bind="attrs"
                large
                color="orionAmber"
                style="float: right"
                v-on="on"
              >
                <v-icon>mdi-download</v-icon>
                <b>Download</b>
              </v-btn>
            </template>

            <v-list class="background lighten-2">
              <v-list-item
                link
                color="red"
                href="/projectsassets/ogun/docs/OGUN.pdf"
              >
                <v-list-item-icon>
                  <v-icon color="red">mdi-adobe-acrobat</v-icon>
                </v-list-item-icon>
                <v-list-item-content>
                  <v-list-item-title><b>PDF File</b></v-list-item-title>
                </v-list-item-content>
              </v-list-item>
              <v-list-item link href="/projectsassets/ogun/docs/OGUN.key">
                <v-list-item-icon>
                  <v-icon color="blue">mdi-presentation</v-icon>
                </v-list-item-icon>
                <v-list-item-content>
                  <v-list-item-title><b>Apple Keynote</b></v-list-item-title>
                </v-list-item-content>
              </v-list-item>
              <v-list-item
                link
                color="red"
                href="/projectsassets/ogun/docs/OGUN.pptx"
              >
                <v-list-item-icon>
                  <v-icon color="amber">mdi-file-powerpoint</v-icon>
                </v-list-item-icon>
                <v-list-item-content>
                  <v-list-item-title
                    ><b>Microsoft PowerPoint</b></v-list-item-title
                  >
                </v-list-item-content>
              </v-list-item>
            </v-list>
          </v-menu>
        </v-col>
      </v-row>
      <v-divider />
      <v-row justify="center" class="logo-holder">
        <v-col cols="12" :xs="12" :lg="4" :md="6">
          <v-img
            src="/imgs/projects/ogun-white.png"
            contain
            max-width="400px"
            class="animate__animated animate__fadeInLeft delay"
          />
        </v-col>
        <v-col cols="12" :xs="12">
          <div class="text-center animate__animated animate__fadeInRight delay">
            <span class="logo-sub-2">Brought to you by</span
            ><span class="logo-sub-founder"> </span
            ><span class="font-weight-bold logo-sub-founder">ORION</span>
          </div>
        </v-col>
      </v-row>
      <v-divider class="mb-10" />
    </div>
    <div>
      <!-- <div> -->
      <!-- <img src="/projects/ogun/imgs/background03.jpg" width="100%" /> -->
      <!-- </div> -->
      <div>
        <span class="cls_010 orionAmber--text title">Content</span>
      </div>
      <div class="cls_011 bullet">
        <span class="cls_011 dotter orionTeal--text">•</span
        ><span class="cls_012"> ORION - Introduction</span>
      </div>
      <div class="cls_011 bullet">
        <span class="cls_011 dotter orionTeal--text">•</span
        ><span class="cls_012"> System Modules</span>
      </div>
      <div class="cls_011 bullet">
        <span class="cls_011 dotter orionTeal--text">•</span
        ><span class="cls_012"> Expectations</span>
      </div>
    </div>
    <div>
      <!-- <div> -->
      <!-- <img src="/projects/ogun/imgs/background04.jpg" width="100%" /> -->
      <!-- </div> -->
      <br />
      <div>
        <span class="cls_010 mt-10 super-title orionAmber--text"
          >ORION - Introduction</span
        >
      </div>
      <div class="cls_013 bullet">
        <span class="cls_013 dotter orionTeal--text">•</span
        ><span class="cls_014">
          ORION is a software solutions company running from 2015 all the way up
          till</span
        >
      </div>
      <div class="cls_014 bullet">
        <span class="cls_014">this moment.</span>
      </div>
      <div class="cls_013 bullet">
        <span class="cls_013 dotter orionTeal--text">•</span
        ><span class="cls_014 bullet">
          We cooperate with companies from all over the globe to find them
          cutting-</span
        >
      </div>
      <div class="cls_014 bullet">
        <span class="cls_014">edge solutions that fit their business.</span>
      </div>
      <div class="cls_013 bullet">
        <span class="cls_013 dotter orionTeal--text">•</span
        ><span class="cls_014 bullet">
          ORION contributes in the software community by many open-source
          packages</span
        >
      </div>
      <div class="cls_014">
        <span class="cls_014 bullet">available for free.</span>
      </div>
      <div class="cls_013">
        <span class="cls_013 bullet dotter orionTeal--text">•</span
        ><span class="cls_014 bullet">
          Companies, Research teams, Factories and even Software-houses are
          using</span
        >
      </div>
      <div class="cls_014 bullet">
        <span class="cls_014">our solutions on daily basis.</span>
      </div>
    </div>
    <div>
      <!-- <div> -->
      <!-- <img src="/projects/ogun/imgs/background05.jpg" width="100%" /> -->
      <!-- </div> -->
      <br />
      <div>
        <span class="cls_010 orionAmber--text super-title">System Modules</span>
      </div>
      <div class="cls_013">
        <br />
        <span
          class="super-subtitle orionTeal--text mt-10 mb-10 cls_013 bullet dotter orionTeal--text"
          >•</span
        ><span class="cls_014 bullet"
          ><a
            href="#manufacturing"
            class="quick-nav blue--text text--lighten-2"
          >
            Manufacturing</a
          ></span
        >
      </div>
      <div class="cls_013">
        <span class="cls_013 bullet dotter orionTeal--text">•</span
        ><span class="cls_014 bullet">
          <a href="#accounting" class="quick-nav blue--text text--lighten-2"
            >Accounting</a
          ></span
        >
      </div>
      <div class="cls_013 bullet">
        <span class="cls_013 bullet dotter orionTeal--text">•</span
        ><span class="cls_014">
          <a href="#hr" class="quick-nav blue--text text--lighten-2"
            >HR and Payroll</a
          ></span
        >
      </div>
      <div class="cls_013 bullet">
        <span class="cls_013 bullet dotter orionTeal--text">•</span
        ><span class="cls_014">
          <a href="#assets" class="quick-nav blue--text text--lighten-2"
            >Asset management.</a
          ></span
        >
      </div>
    </div>
    <div>
      <!-- <div> -->
      <!-- <img src="/projects/ogun/imgs/background06.jpg" width="100%" /> -->
      <!-- </div> -->
      <br />
      <div id="manufacturing" class="cls_012">
        <span class="super-subtitle orionTeal--text mt-10 mb-10 cls_012"
          >Manufacturing</span
        >
      </div>
      <div class="cls_015 bullet">
        <span class="cls_015 bullet">OGUN</span
        ><span class="cls_014">
          Covers all the necessary features for steel manufacturing such
          as:</span
        >
      </div>
      <div class="cls_013 bullet">
        <span class="cls_013 bullet dotter orionTeal--text">•</span
        ><span class="cls_014"> Bill Of Materials Management.</span>
      </div>
      <div class="cls_013 bullet">
        <span class="cls_013 bullet dotter orionTeal--text">•</span
        ><span class="cls_014"> Production planing.</span>
      </div>
      <div class="cls_013 bullet">
        <span class="cls_013 bullet dotter orionTeal--text">•</span
        ><span class="cls_014"> Taking Work Orders.</span>
      </div>
      <div class="cls_013 bullet">
        <span class="cls_013 bullet dotter orionTeal--text">•</span
        ><span class="cls_014"> Downtime entry.</span>
      </div>
    </div>
    <div>
      <!-- <div> -->
      <!-- <img src="/projects/ogun/imgs/background07.jpg" width="100%" /> -->
      <!-- </div> -->
      <br />
      <div class="cls_012">
        <span class="super-subtitle orionTeal--text mt-10 mb-10 cls_012"
          >Manufacturing - Bill Of Materials</span
        >
      </div>
      <div class="cls_014 bullet">
        <span class="cls_014 bullet"
          >A Bill of Materials is a list of items and sub-assemblies with
          quantities required</span
        >
      </div>
      <div class="cls_014 bullet">
        <span class="cls_014 bullet">to manufacture an Item.</span>
      </div>
      <div class="cls_016 bullet">
        <span class="cls_016 bullet dotter orionTeal--text">•</span
        ><span class="cls_014">
          A BOM may also contain the manufacturing operations required to</span
        >
      </div>
      <div class="cls_014 bullet">
        <span class="cls_014 bullet">manufacture the Item.</span>
      </div>
      <div class="cls_016 bullet">
        <span class="cls_016 bullet dotter orionTeal--text">•</span
        ><span class="cls_014"> A </span
        ><span class="cls_017">Bill of Materials</span
        ><span class="cls_014">
          (BOM) is at the heart of the Manufacturing system and the</span
        >
      </div>
      <div class="cls_014 bullet">
        <span class="cls_014 bullet"
          >most important document that will help to create other document types
          like</span
        >
      </div>
      <div class="cls_014 bullet">
        <span class="cls_014 bullet">Work Orders and Job Cards.</span>
      </div>
      <div class="cls_016 bullet">
        <span class="cls_016 bullet dotter orionTeal--text">•</span
        ><span class="cls_014">
          A BOM is the outcome of Items, Operations, Workstations
          combined.</span
        >
      </div>
    </div>
    <div>
      <!-- <div> -->
      <!-- <img src="/projects/ogun/imgs/background08.jpg" width="100%" /> -->
      <!-- </div> -->
      <br />
      <div class="cls_012">
        <span class="super-subtitle orionTeal--text mt-10 mb-10 cls_012"
          >Manufacturing - Bill Of Materials</span
        >
      </div>
      <div class="cls_014 bullet">
        <span class="cls_014 bullet"
          >This is an example of how BOM looks like:</span
        >
      </div>
      <div class="cls_016 bullet">
        <span class="cls_016 bullet dotter orionTeal--text">•</span
        ><span class="cls_014"> The quantity of Raw Material used.</span>
      </div>
      <div class="cls_016 bullet">
        <span class="cls_016 bullet dotter orionTeal--text">•</span
        ><span class="cls_014">
          Item operation to be fetched in Work Orders later.</span
        >
      </div>
      <div class="cls_016 bullet">
        <span class="cls_016 bullet dotter orionTeal--text">•</span
        ><span class="cls_014"> Source Warehouse to track inventory.</span>
      </div>
      <div class="cls_016 bullet">
        <span class="cls_016 bullet dotter orionTeal--text">•</span
        ><span class="cls_014"> Remaining scrap percentage.</span>
      </div>
    </div>
    <div>
      <!-- <div> -->
      <!-- <img src="/projects/ogun/imgs/background09.jpg" width="100%" /> -->
      <!-- </div> -->
      <br />
      <div class="cls_012">
        <span class="super-subtitle orionTeal--text mt-10 mb-10 cls_012"
          >Manufacturing - Production Plan</span
        >
      </div>
      <div class="cls_016 bullet">
        <span class="cls_016 bullet dotter orionTeal--text">•</span
        ><span class="cls_014">
          A Production Plan helps in production and material planning for the
          Items</span
        >
      </div>
      <div class="cls_014 bullet">
        <span class="cls_014 bullet">planned for manufacturing.</span>
      </div>
      <div class="cls_016 bullet">
        <span class="cls_016 bullet dotter orionTeal--text">•</span
        ><span class="cls_014">
          These production items can be committed via Sales Order (to Customers)
          or</span
        >
      </div>
      <div class="cls_014 bullet">
        <span class="cls_014 bullet">Material Requests (internally).</span>
      </div>
      <div class="cls_016 bullet">
        <span class="cls_016 bullet dotter orionTeal--text">•</span
        ><span class="cls_014">
          It also helps to plan production against multiple Sales Orders or the
          Material</span
        >
      </div>
      <div class="cls_014 bullet">
        <span class="cls_014 bullet">Requests.</span>
      </div>
      <div class="cls_016 bullet">
        <span class="cls_016 bullet dotter orionTeal--text">•</span
        ><span class="cls_014">
          A Production Plan helps in Material Procurement planning for the raw
          material</span
        >
      </div>
      <div>
        <span class="cls_014"
          >item, based on the quantity of finished products to be
          manufactured.</span
        >
      </div>
    </div>
    <div>
      <!-- <div> -->
      <!-- <img src="/projects/ogun/imgs/background10.jpg" width="100%" /> -->
      <!-- </div> -->
      <br />
      <div class="cls_012">
        <span class="super-subtitle orionTeal--text mt-10 mb-10 cls_012"
          >Manufacturing - Production Plan</span
        >
      </div>
      <div class="cls_014 bullet">
        <span class="cls_014 bullet"
          >As mentioned earlier, a Production Plan can be used for planning
          the</span
        >
      </div>
      <div class="cls_014 bullet">
        <span class="cls_014 bullet"
          >manufacture of Items against Sales Orders or Material Requests.</span
        >
      </div>
      <div class="cls_014 bullet">
        <span class="cls_014 bullet"
          >For Example; this is how Production against Sales order looks
          like:</span
        >
      </div>
      <div class="cls_016 bullet">
        <span class="cls_016 bullet dotter orionTeal--text">•</span
        ><span class="cls_014"> The quantity of Raw Material used.</span>
      </div>
      <div class="cls_016 bullet">
        <span class="cls_016 bullet dotter orionTeal--text">•</span
        ><span class="cls_014">
          Item operation to be fetched in Work Orders later.</span
        >
      </div>
      <div class="cls_016 bullet">
        <span class="cls_016 bullet dotter orionTeal--text">•</span
        ><span class="cls_014"> Source Warehouse to track inventory.</span>
      </div>
      <div class="cls_016 bullet">
        <span class="cls_016 bullet dotter orionTeal--text">•</span
        ><span class="cls_014"> Remaining scrap percentage.</span>
      </div>
    </div>
    <div>
      <!-- <div> -->
      <!-- <img src="/projects/ogun/imgs/background11.jpg" width="100%" /> -->
      <!-- </div> -->
      <br />
      <div class="cls_012">
        <span class="super-subtitle orionTeal--text mt-10 mb-10 cls_012"
          >Manufacturing - Work Orders</span
        >
      </div>
      <div class="cls_014 bullet">
        <span class="cls_014 bullet"
          >Woking Orders is your tool to flash the green light for new
          orders.</span
        >
      </div>
      <div class="cls_016 bullet">
        <span class="cls_016 bullet dotter orionTeal--text">•</span
        ><span class="cls_014"> Select the Item to be manufactured.</span>
      </div>
      <div class="cls_016 bullet">
        <span class="cls_016 bullet dotter orionTeal--text">•</span
        ><span class="cls_014"> Select the Bill Of Material (BOM).</span>
      </div>
      <div class="cls_016 bullet">
        <span class="cls_016 bullet dotter orionTeal--text">•</span
        ><span class="cls_014"> Set the quantity to manufacture.</span>
      </div>
      <div class="cls_016 bullet">
        <span class="cls_016 bullet dotter orionTeal--text">•</span
        ><span class="cls_014"> Set the planned start/end date.</span>
      </div>
    </div>
    <div>
      <!-- <div> -->
      <!-- <img src="/projects/ogun/imgs/background12.jpg" width="100%" /> -->
      <!-- </div> -->
      <br />
      <div class="cls_012">
        <span class="super-subtitle orionTeal--text mt-10 mb-10 cls_012"
          >Manufacturing - Down time Entry</span
        >
      </div>
      <div class="cls_018 bullet">
        <span class="cls_018 bullet dotter orionTeal--text">•</span
        ><span class="cls_014">
          Downtime Entry document is used to capture</span
        >
      </div>
      <div class="cls_014 bullet">
        <span class="cls_014 bullet">the machine's Downtime in minutes.</span>
      </div>
      <div class="cls_018 bullet">
        <span class="cls_018 bullet dotter orionTeal--text">•</span
        ><span class="cls_014"> User needs to manually create the</span>
      </div>
      <div class="cls_014 bullet">
        <span class="cls_014 bullet"
          >downtime record by selecting the proper</span
        >
      </div>
      <div class="cls_014 bullet">
        <span class="cls_014 bullet"
          >machine alongwith the machine's downtime.</span
        >
      </div>
      <div class="cls_018 bullet">
        <span class="cls_018 bullet dotter orionTeal--text">•</span
        ><span class="cls_014"> Using Downtime entry data operator knows</span>
      </div>
      <div class="cls_014 bullet">
        <span class="cls_014 bullet"
          >which machine not performing well and</span
        >
      </div>
      <div>
        <span class="cls_014">needs maintenance.</span>
      </div>
    </div>
    <div>
      <!-- <div> -->
      <!-- <img src="/projects/ogun/imgs/background13.jpg" width="100%" /> -->
      <!-- </div> -->
      <br />
      <div id="accounting" class="cls_012">
        <span class="super-subtitle orionTeal--text mt-10 mb-10 cls_012"
          >Accounting</span
        >
      </div>
      <div class="cls_014 bullet">
        <span class="cls_014 bullet"
          >At the end of sales and purchase cycle comes billing and payments,
          You may</span
        >
      </div>
      <div class="cls_014 bullet">
        <span class="cls_014 bullet"
          >have an accountant in your team, or you may be doing accounting
          yourself, or</span
        >
      </div>
      <div class="cls_014 bullet">
        <span class="cls_014 bullet"
          >you may have outsourced your accounting.</span
        >
      </div>
      <div class="cls_014 bullet">
        <span class="cls_014 bullet"
          >In all the cases financial accounting forms the core of any
          business</span
        >
      </div>
      <div>
        <span class="cls_014">management system like an ERP.</span>
      </div>
    </div>
    <div>
      <div class="cls_014 bullet">
        <span class="cls_014 bullet">in </span><span class="cls_015">OGUN</span
        ><span class="cls_014"
          >; your accounting operations consists of 3 main transactions:</span
        >
      </div>
      <div class="cls_018 bullet">
        <span class="cls_018 bullet dotter orionTeal--text">•</span
        ><span class="cls_014"> Sales Invoice</span>
      </div>
      <div class="cls_018 bullet">
        <span class="cls_018 bullet dotter orionTeal--text">•</span
        ><span class="cls_014"> Purchase Invoice</span>
      </div>
      <div class="cls_018 bullet">
        <span class="cls_018 bullet dotter orionTeal--text">•</span
        ><span class="cls_014"> Journal Entries</span>
      </div>
    </div>
    <div>
      <!-- <div> -->
      <!-- <img src="/projects/ogun/imgs/background15.jpg" width="100%" /> -->
      <!-- </div> -->
      <br />
      <div class="cls_012">
        <span class="super-subtitle orionTeal--text mt-10 mb-10 cls_012"
          >Accounting - Sales Invoice</span
        >
      </div>
      <div class="cls_019 bullet">
        <span class="cls_019 bullet dotter orionTeal--text">•</span
        ><span class="cls_020">
          A Sales Invoice is a bill that you send to your customers, against
          which the customer processes the payment.</span
        >
      </div>
      <div class="cls_019 bullet">
        <span class="cls_019 bullet dotter orionTeal--text">•</span
        ><span class="cls_020">
          Sales Invoice is an accounting transaction.</span
        >
      </div>
      <div class="cls_019 bullet">
        <span class="cls_019 bullet dotter orionTeal--text">•</span
        ><span class="cls_020">
          On submission of Sales Invoice, the system updates the receivable and
          books income against a Customer</span
        >
      </div>
      <div class="cls_020 bullet">
        <span class="cls_020 bullet">Account.</span>
      </div>
      <div class="cls_019 bullet">
        <span class="cls_019 bullet dotter orionTeal--text">•</span
        ><span class="cls_020">
          Sales Invoice will also give you the following:</span
        >
      </div>
      <div class="cls_019 bullet">
        <span class="cls_019 bullet dotter orionTeal--text">•</span
        ><span class="cls_020"> Accounting Impact</span>
      </div>
      <div class="cls_019 bullet">
        <span class="cls_019 bullet dotter orionTeal--text">•</span
        ><span class="cls_020">
          Accounting entries (GL Entry) for a typical double entry “Sale”</span
        >
      </div>
      <div class="cls_019 bullet">
        <span class="cls_019 bullet dotter orionTeal--text">•</span
        ><span class="cls_020"> Automatically Fetching Item Batch Numbers</span>
      </div>
      <div class="cls_019 bullet">
        <span class="cls_019 bullet dotter orionTeal--text">•</span
        ><span class="cls_020"> POS Invoices</span>
      </div>
      <div class="cls_019 bullet">
        <span class="cls_019 bullet dotter orionTeal--text">•</span
        ><span class="cls_020"> Billing Timesheet with Project</span>
      </div>
    </div>
    <div>
      <!-- <div> -->
      <!-- <img src="/projects/ogun/imgs/background16.jpg" width="100%" /> -->
      <!-- </div> -->
      <br />
      <div class="cls_012">
        <span class="super-subtitle orionTeal--text mt-10 mb-10 cls_012"
          >Accounting - Purchase Invoice</span
        >
      </div>
      <div class="cls_021 bullet">
        <span class="cls_021 bullet dotter orionTeal--text">•</span
        ><span class="cls_022">
          A Purchase Invoice is the exact opposite of your Sales Invoice.</span
        >
      </div>
      <div class="cls_021 bullet">
        <span class="cls_021 bullet dotter orionTeal--text">•</span
        ><span class="cls_022">
          It is the bill that your Supplier sends you for products or services
          delivered.</span
        >
      </div>
      <div class="cls_021 bullet">
        <span class="cls_021 bullet dotter orionTeal--text">•</span
        ><span class="cls_022">
          Here you accrue expenses to your Supplier.</span
        >
      </div>
      <div class="cls_021 bullet">
        <span class="cls_021 bullet dotter orionTeal--text">•</span
        ><span class="cls_022">
          Making a Purchase Invoice is very similar to making a Purchase
          Order.</span
        >
      </div>
      <div class="cls_021 bullet">
        <span class="cls_021 bullet dotter orionTeal--text">•</span
        ><span class="cls_022">
          Purchase Invoice will also give you the following:</span
        >
      </div>
      <div class="cls_021 bullet">
        <span class="cls_021 bullet dotter orionTeal--text">•</span
        ><span class="cls_022">
          accounting Treatment When Is Paid is checked</span
        >
      </div>
      <div class="cls_021 bullet">
        <span class="cls_021 bullet dotter orionTeal--text">•</span
        ><span class="cls_022"> Is purchase an “Expense” or an “Asset?</span>
      </div>
      <div class="cls_021 bullet">
        <span class="cls_021 bullet dotter orionTeal--text">•</span
        ><span class="cls_022"> Deducting Taxes at Source</span>
      </div>
      <div class="cls_021 bullet">
        <span class="cls_021 bullet dotter orionTeal--text">•</span
        ><span class="cls_022">
          Hold Payments for a Purchase Invoice/Explicit Hold, Date Span
          Hold</span
        >
      </div>
      <div class="cls_023 bullet">
        <span class="cls_023 bullet dotter orionTeal--text">•</span>
      </div>
    </div>
    <div>
      <!-- <div> -->
      <!-- <img src="/projects/ogun/imgs/background17.jpg" width="100%" /> -->
      <!-- </div> -->
      <br />
      <div class="cls_012">
        <span class="super-subtitle orionTeal--text mt-10 mb-10 cls_012"
          >Accounting - Journal Entry</span
        >
      </div>
      <div class="cls_024 bullet">
        <span class="cls_024 bullet dotter orionTeal--text">•</span
        ><span class="cls_025">
          All types of accounting entries other than </span
        ><span class="cls_026">Sales Invoice </span
        ><span class="cls_025">and </span
        ><span class="cls_026">Purchase Invoice </span
        ><span class="cls_025">are made using the</span>
      </div>
      <div class="cls_026 bullet">
        <span class="cls_026 bullet">Journal Entry</span
        ><span class="cls_025">.</span>
      </div>
      <div class="cls_024 bullet">
        <span class="cls_024 bullet dotter orionTeal--text">•</span
        ><span class="cls_025"> A </span
        ><span class="cls_027">Journal Entry </span
        ><span class="cls_025"
          >is a standard accounting transaction that affects multiple Accounts
          and the sum of</span
        >
      </div>
      <div class="cls_025 bullet">
        <span class="cls_025 bullet"
          >debits is equal to the sum of credits.</span
        >
      </div>
      <div class="cls_024 bullet">
        <span class="cls_024 bullet dotter orionTeal--text">•</span
        ><span class="cls_025">
          Journal Entry will also give you the following:</span
        >
      </div>
      <div class="cls_024 bullet">
        <span class="cls_024 bullet dotter orionTeal--text">•</span
        ><span class="cls_025"> Common Entries</span>
      </div>
      <div class="cls_024 bullet">
        <span class="cls_024 bullet dotter orionTeal--text">•</span
        ><span class="cls_025"> Expenses</span>
      </div>
      <div class="cls_024 bullet">
        <span class="cls_024 bullet dotter orionTeal--text">•</span
        ><span class="cls_025"> Bad Debts or Write Offs</span>
      </div>
      <div class="cls_024 bullet">
        <span class="cls_024 bullet dotter orionTeal--text">•</span
        ><span class="cls_025"> Deprecation</span>
      </div>
      <div class="cls_024 bullet">
        <span class="cls_024 bullet dotter orionTeal--text">•</span
        ><span class="cls_025"> Credit and Debit Notes</span>
      </div>
    </div>
    <div>
      <!-- <div> -->
      <!-- <img src="/projects/ogun/imgs/background18.jpg" width="100%" /> -->
      <!-- </div> -->
      <br />
      <div class="cls_012">
        <span class="super-subtitle orionTeal--text mt-10 mb-10 cls_012"
          >Accounting - Financial Statements</span
        >
      </div>
      <div class="cls_014 bullet">
        <span class="cls_014 bullet"
          >Now that you have recorded all the information, you can check where
          your</span
        >
      </div>
      <div class="cls_014 bullet">
        <span class="cls_014 bullet"
          >business stands using the financial statements.</span
        >
      </div>
      <div class="cls_015 bullet">
        <span class="cls_015 bullet">Profit and Loss Statement:</span>
      </div>
      <div class="cls_014 bullet">
        <span class="cls_014 bullet"
          >Profit and loss statement reports a company’s</span
        >
      </div>
      <div class="cls_014 bullet">
        <span class="cls_014 bullet"
          >revenues, expenses, and most of the gains</span
        >
      </div>
      <div class="cls_014 bullet">
        <span class="cls_014 bullet">and losses which occurred during</span>
      </div>
      <div class="cls_014 bullet">
        <span class="cls_014 bullet"
          >the period of time specified in its heading.</span
        >
      </div>
    </div>
    <div>
      <!-- <div> -->
      <!-- <img src="/projects/ogun/imgs/background19.jpg" width="100%" /> -->
      <!-- </div> -->
      <br />
      <div class="cls_012">
        <span class="super-subtitle orionTeal--text mt-10 mb-10 cls_012"
          >Accounting - Financial Statements</span
        >
      </div>
      <div class="cls_015 bullet">
        <span class="cls_015 bullet">Balance Sheet:</span
        ><span class="cls_014">
          Balance sheet report shows a company’s assets,</span
        >
      </div>
      <div class="cls_014 bullet">
        <span class="cls_014 bullet"
          >it’s liabilities, and its stockholders’ equity.</span
        >
      </div>
    </div>
    <div>
      <!-- <div> -->
      <!-- <img src="/projects/ogun/imgs/background20.jpg" width="100%" /> -->
      <!-- </div> -->
      <br />
      <div class="cls_012">
        <span class="super-subtitle orionTeal--text mt-10 mb-10 cls_012"
          >Accounting - Financial Statements</span
        >
      </div>
      <div class="cls_015 bullet">
        <span class="cls_015 bullet">Cash Flow: </span
        ><span class="cls_014"
          >The cash flow statement reports a company’s major sources and</span
        >
      </div>
      <div class="cls_014 bullet">
        <span class="cls_014 bullet">uses of cash.</span>
      </div>
    </div>
    <div>
      <!-- <div> -->
      <!-- <img src="/projects/ogun/imgs/background21.jpg" width="100%" /> -->
      <!-- </div> -->
      <br />
      <div id="hr" class="cls_012">
        <span class="super-subtitle orionTeal--text mt-10 mb-10 cls_012"
          >HR and Payroll</span
        >
      </div>
      <div class="cls_028 bullet">
        <span class="cls_028 bullet"
          >Leave and Attendance Tracking, Expense Claims, Salary and Payroll,
          Recruitment, Performance and more are all</span
        >
      </div>
      <div class="cls_028 bullet">
        <span class="cls_028 bullet"
          >handled with OGUN HR and Payroll Module</span
        >
      </div>
      <div class="cls_029 bullet">
        <span class="cls_029 bullet">Employee</span>
      </div>
      <div class="cls_030 bullet">
        <span class="cls_030 bullet dotter orionTeal--text">•</span
        ><span class="cls_031"> Employment Type</span>
      </div>
      <div class="cls_030 bullet">
        <span class="cls_030 bullet dotter orionTeal--text">•</span
        ><span class="cls_031">
          Various employment contracts you have with your employees.</span
        >
      </div>
      <div class="cls_030 bullet">
        <span class="cls_030 bullet dotter orionTeal--text">•</span
        ><span class="cls_031"> Department</span>
      </div>
      <div class="cls_030 bullet">
        <span class="cls_030 bullet dotter orionTeal--text">•</span
        ><span class="cls_031">
          You can configure the Departments in your organization and assign them
          to your employees</span
        >
      </div>
      <div class="cls_030 bullet">
        <span class="cls_030 bullet dotter orionTeal--text">•</span
        ><span class="cls_031"> Health Insurance</span>
      </div>
      <div class="cls_030 bullet">
        <span class="cls_030 bullet dotter orionTeal--text">•</span
        ><span class="cls_031">
          You can manage health insurance for your employees within OGUN</span
        >
      </div>
      <div class="cls_030 bullet">
        <span class="cls_030 bullet dotter orionTeal--text">•</span
        ><span class="cls_031"> HR Settings</span>
      </div>
      <div class="cls_030 bullet">
        <span class="cls_030 bullet dotter orionTeal--text">•</span
        ><span class="cls_031">
          Global settings for HR related documents and workflow</span
        >
      </div>
    </div>
    <div>
      <!-- <div> -->
      <!-- <img src="/projects/ogun/imgs/background22.jpg" width="100%" /> -->
      <!-- </div> -->
      <br />
      <div class="cls_012">
        <span class="super-subtitle orionTeal--text mt-10 mb-10 cls_012"
          >HR and Payroll - Recruitment</span
        >
      </div>
      <div class="cls_032 bullet">
        <span class="cls_032 bullet dotter orionTeal--text">•</span
        ><span class="cls_033"> Staffing Plan</span>
      </div>
      <div class="cls_032 bullet">
        <span class="cls_032 bullet dotter orionTeal--text">•</span
        ><span class="cls_033">
          OGUN allows you to efficiently plan and budget new hiring for a
          period.</span
        >
      </div>
      <div>
        <span class="cls_032 dotter orionTeal--text">•</span
        ><span class="cls_033"> Job Opening</span>
      </div>
      <div class="cls_034 bullet">
        <span class="cls_034 bullet dotter orionTeal--text">•</span
        ><span class="cls_035">
          You can make a record of the open vacancies in your company using Job
          Opening.</span
        >
      </div>
      <div class="cls_032 bullet">
        <span class="cls_032 bullet dotter orionTeal--text">•</span
        ><span class="cls_033"> Job Applicant</span>
      </div>
      <div class="cls_034 bullet">
        <span class="cls_034 bullet dotter orionTeal--text">•</span
        ><span class="cls_035">
          You can maintain a list of People who have applied for a Job
          Opening.</span
        >
      </div>
      <div class="cls_032 bullet">
        <span class="cls_032 bullet dotter orionTeal--text">•</span
        ><span class="cls_033"> Job Offer</span>
      </div>
      <div class="cls_034 bullet">
        <span class="cls_034 bullet dotter orionTeal--text">•</span
        ><span class="cls_035">
          Job Offer is given to selected candidates after Interview & selection
          which states the terms of</span
        >
      </div>
      <div class="cls_035 bullet">
        <span class="cls_035 bullet">their employment.</span>
      </div>
    </div>
    <div>
      <!-- <div> -->
      <!-- <img src="/projects/ogun/imgs/background23.jpg" width="100%" /> -->
      <!-- </div> -->
      <br />
      <div class="cls_012">
        <span class="super-subtitle orionTeal--text mt-10 mb-10 cls_012"
          >HR and Payroll - Leave Management</span
        >
      </div>
      <div class="cls_036 bullet">
        <span class="cls_036 bullet dotter orionTeal--text">•</span
        ><span class="cls_037"> Leave Type</span>
      </div>
      <div class="cls_038 bullet">
        <span class="cls_038 bullet dotter orionTeal--text">•</span
        ><span class="cls_039">
          Leave Type refers to types of leave allotted to an employee by a
          company.</span
        >
      </div>
      <div class="cls_036 bullet">
        <span class="cls_036 bullet dotter orionTeal--text">•</span
        ><span class="cls_037"> Leave Period</span>
      </div>
      <div class="cls_038 bullet">
        <span class="cls_038 bullet dotter orionTeal--text">•</span
        ><span class="cls_039">
          You can manage leaves based on a Leave Period, corresponding to a
          calendar year or the fiscal year.</span
        >
      </div>
      <div class="cls_036 bullet">
        <span class="cls_036 bullet dotter orionTeal--text">•</span
        ><span class="cls_037"> Leave Allocation</span>
      </div>
      <div class="cls_038 bullet">
        <span class="cls_038 bullet dotter orionTeal--text">•</span
        ><span class="cls_039">
          Leave Allocation enables you to allot a specific number of leaves to a
          particular employee.</span
        >
      </div>
      <div class="cls_036 bullet">
        <span class="cls_036 bullet dotter orionTeal--text">•</span
        ><span class="cls_037"> Leave Application</span>
      </div>
      <div class="cls_038 bullet">
        <span class="cls_038 bullet dotter orionTeal--text">•</span
        ><span class="cls_039">
          Employees can formally apply for a leave and can track it's
          approval.</span
        >
      </div>
      <div class="cls_036 bullet">
        <span class="cls_036 bullet dotter orionTeal--text">•</span
        ><span class="cls_037"> Leave Encashment</span>
      </div>
      <div class="cls_038 bullet">
        <span class="cls_038 bullet dotter orionTeal--text">•</span
        ><span class="cls_039">
          For Leave Types which are encashable, you can submit Leave
          Encashment.</span
        >
      </div>
      <div class="cls_036 bullet">
        <span class="cls_036 bullet dotter orionTeal--text">•</span
        ><span class="cls_037"> Holiday List</span>
      </div>
      <div class="cls_038 bullet">
        <span class="cls_038 bullet dotter orionTeal--text">•</span
        ><span class="cls_039">
          Holiday List is a list which contains the dates of holidays.</span
        >
      </div>
      <div class="cls_036 bullet">
        <span class="cls_036 bullet dotter orionTeal--text">•</span
        ><span class="cls_037"> Leave Block List</span>
      </div>
      <div class="cls_038 bullet">
        <span class="cls_038 bullet dotter orionTeal--text">•</span
        ><span class="cls_039">
          Leave Block List is a list of dates in a year, on which employees can
          not apply for leave</span
        >
      </div>
    </div>
    <div>
      <!-- <div> -->
      <!-- <img src="/projects/ogun/imgs/background24.jpg" width="100%" /> -->
      <!-- </div> -->
      <br />
      <div class="cls_012">
        <span class="super-subtitle orionTeal--text mt-10 mb-10 cls_012"
          >HR and Payroll - Attendance</span
        >
      </div>
      <div>
        <span class="cls_040 dotter orionTeal--text">•</span
        ><span class="cls_041">
          Attendance is the record stating that an Employee has been present on
          a particular day.</span
        >
      </div>
      <div class="cls_040 bullet">
        <span class="cls_040 bullet dotter orionTeal--text">•</span
        ><span class="cls_041"> Attendance Request</span>
      </div>
      <div class="cls_042 bullet">
        <span class="cls_042 bullet dotter orionTeal--text">•</span
        ><span class="cls_043">
          Employees can submit their attendance request for the days when their
          attendance wasn't</span
        >
      </div>
      <div class="cls_043 bullet">
        <span class="cls_043 bullet">marked.</span>
      </div>
      <div class="cls_040 bullet">
        <span class="cls_040 bullet dotter orionTeal--text">•</span
        ><span class="cls_041"> Upload Attendance</span>
      </div>
      <div class="cls_042 bullet">
        <span class="cls_042 bullet dotter orionTeal--text">•</span
        ><span class="cls_043">
          This tool helps you to upload bulk attendance from a CSV (Excel)
          file.</span
        >
      </div>
      <div class="cls_040 bullet">
        <span class="cls_040 bullet dotter orionTeal--text">•</span
        ><span class="cls_041"> Auto Attendance</span>
      </div>
      <div class="cls_042 bullet">
        <span class="cls_042 bullet dotter orionTeal--text">•</span
        ><span class="cls_043">
          Auto attendance marks the attendance for the Employees assigned to a
          shift based on</span
        >
      </div>
      <div class="cls_043 bullet">
        <span class="cls_043 bullet"
          >records in the 'Employee Checkin' Document</span
        >
      </div>
    </div>
    <div>
      <!-- <div> -->
      <!-- <img src="/projects/ogun/imgs/background25.jpg" width="100%" /> -->
      <!-- </div> -->
      <br />
      <div class="cls_012">
        <span class="super-subtitle orionTeal--text mt-10 mb-10 cls_012"
          >HR and Payroll - Lifecycle and Salary</span
        >
      </div>
      <div class="cls_044 bullet">
        <span class="cls_044 bullet dotter orionTeal--text">•</span
        ><span class="cls_045"> Appraisal</span>
      </div>
      <div class="cls_046 bullet">
        <span class="cls_046 bullet dotter orionTeal--text">•</span
        ><span class="cls_047">
          You can manage appraisals by creating templates for each role with the
          parameters with appropriate weightage to each parameter.</span
        >
      </div>
      <div class="cls_044 bullet">
        <span class="cls_044 bullet dotter orionTeal--text">•</span
        ><span class="cls_045"> Employee Onboarding</span>
      </div>
      <div class="cls_046 bullet">
        <span class="cls_046 bullet dotter orionTeal--text">•</span
        ><span class="cls_047">
          For the process of hiring an employee you can create a set of Tasks at
          the time of each Employee.</span
        >
      </div>
      <div class="cls_044 bullet">
        <span class="cls_044 bullet dotter orionTeal--text">•</span
        ><span class="cls_045"> Employee Skill Map</span>
      </div>
      <div class="cls_046 bullet">
        <span class="cls_046 bullet dotter orionTeal--text">•</span
        ><span class="cls_047">
          Employee Skill Map is a record which helps your organization track
          your Employee's skill sets and trainings.</span
        >
      </div>
      <div class="cls_044 bullet">
        <span class="cls_044 bullet dotter orionTeal--text">•</span
        ><span class="cls_045"> Employee Promotion</span>
      </div>
      <div class="cls_046 bullet">
        <span class="cls_046 bullet dotter orionTeal--text">•</span
        ><span class="cls_047">
          You can manage Employee Promotions using this document.</span
        >
      </div>
      <div class="cls_044 bullet">
        <span class="cls_044 bullet dotter orionTeal--text">•</span
        ><span class="cls_045"> Employee Transfer</span>
      </div>
      <div class="cls_046 bullet">
        <span class="cls_046 bullet dotter orionTeal--text">•</span
        ><span class="cls_047">
          You can transfer Employees to different Company or Department by using
          Employee Transfer.</span
        >
      </div>
      <div class="cls_044 bullet">
        <span class="cls_044 bullet dotter orionTeal--text">•</span
        ><span class="cls_045"> Employee Separation</span>
      </div>
      <div class="cls_046 bullet">
        <span class="cls_046 bullet dotter orionTeal--text">•</span
        ><span class="cls_047">
          For the process of relieving an employee you can create a set of Task
          at the time of each Employee.</span
        >
      </div>
    </div>
    <div>
      <!-- <div> -->
      <!-- <img src="/projects/ogun/imgs/background26.jpg" width="100%" /> -->
      <!-- </div> -->
      <br />
      <div class="cls_012">
        <span class="super-subtitle orionTeal--text mt-10 mb-10 cls_012"
          >HR and Payroll - Payroll</span
        >
      </div>
      <div>
        <span class="cls_048 dotter orionTeal--text">•</span
        ><span class="cls_049"> Payroll Entry</span>
      </div>
      <div class="cls_050 bullet">
        <span class="cls_050 bullet dotter orionTeal--text">•</span
        ><span class="cls_051">
          Payroll Entry enables bulk processing of payroll for employees company
          wide or employees of a particular branch, department or
          designation.</span
        >
      </div>
      <div class="cls_048 bullet">
        <span class="cls_048 bullet dotter orionTeal--text">•</span
        ><span class="cls_049"> Additional Salary</span>
      </div>
      <div class="cls_050 bullet">
        <span class="cls_050 bullet dotter orionTeal--text">•</span
        ><span class="cls_051">
          OGUN allows you to add additional Salary Components to Salary Slips
          while processing the payroll.</span
        >
      </div>
      <div class="cls_048 bullet">
        <span class="cls_048 bullet dotter orionTeal--text">•</span
        ><span class="cls_049"> Employee Benefit Application</span>
      </div>
      <div class="cls_050 bullet">
        <span class="cls_050 bullet dotter orionTeal--text">•</span
        ><span class="cls_051">
          Employees are entitled to flexible benefits which they can either
          receive pro-rata or as a lump-sum amount when they claim the
          benefit.</span
        >
      </div>
      <div class="cls_048 bullet">
        <span class="cls_048 bullet dotter orionTeal--text">•</span
        ><span class="cls_049"> Employee Tax Exemption Declaration</span>
      </div>
      <div class="cls_050 bullet">
        <span class="cls_050 bullet dotter orionTeal--text">•</span
        ><span class="cls_051">
          Employees can declare the contributions they plan to do in the payroll
          period which will reduce their net taxable income for the entire
          payroll period.</span
        >
      </div>
      <div class="cls_048 bullet">
        <span class="cls_048 bullet dotter orionTeal--text">•</span
        ><span class="cls_049"> Payroll Period</span>
      </div>
      <div class="cls_050 bullet">
        <span class="cls_050 bullet dotter orionTeal--text">•</span
        ><span class="cls_051">
          Payroll Period helps you define Salary Structures and to calculate tax
          for a specific period based on applicable Income Tax Slab</span
        >
      </div>
      <div class="cls_048 bullet">
        <span class="cls_048 bullet dotter orionTeal--text">•</span
        ><span class="cls_049"> Income Tax Slab</span>
      </div>
      <div class="cls_050 bullet">
        <span class="cls_050 bullet dotter orionTeal--text">•</span
        ><span class="cls_051">
          Income Tax Slab helps to define income tax rates based on different
          taxable income slab</span
        >
      </div>
      <div class="cls_048 bullet">
        <span class="cls_048 bullet dotter orionTeal--text">•</span
        ><span class="cls_049"> Payroll Setup</span>
      </div>
      <div class="cls_050 bullet">
        <span class="cls_050 bullet dotter orionTeal--text">•</span
        ><span class="cls_051">
          Salary is a fixed amount of money or compensation paid to an employee
          by an employer in return for the work performed.</span
        >
      </div>
      <div>
        <span class="cls_048 dotter orionTeal--text">•</span
        ><span class="cls_049"> Setting Up Tax</span>
      </div>
      <div class="cls_050 bullet">
        <span class="cls_050 bullet dotter orionTeal--text">•</span
        ><span class="cls_051">
          In many countries regulations allow exempting a part of some type of
          spendings by individuals from being added to their annual taxable
          income</span
        >
      </div>
    </div>
    <div>
      <!-- <div> -->
      <!-- <img src="/projects/ogun/imgs/background27.jpg" width="100%" /> -->
      <!-- </div> -->
      <br />
      <div class="cls_012">
        <span class="super-subtitle orionTeal--text mt-10 mb-10 cls_012"
          >HR and Payroll - Employee</span
        >
      </div>
      <div class="cls_052 bullet">
        <span class="cls_052 bullet">In </span><span class="cls_053">OGUN</span
        ><span class="cls_052">, you can manage Employee master.</span>
      </div>
      <div class="cls_052 bullet">
        <span class="cls_052 bullet"
          >The Employee master captures demographics, personal and professional
          details.</span
        >
      </div>
      <div class="cls_052 bullet">
        <span class="cls_052 bullet"
          >You can further use this Employee master for performing various HR
          functions like:</span
        >
      </div>
      <div class="cls_054 bullet">
        <span class="cls_054 bullet dotter orionTeal--text">•</span
        ><span class="cls_052"> Processing Payroll</span>
      </div>
      <div class="cls_054 bullet">
        <span class="cls_054 bullet dotter orionTeal--text">•</span
        ><span class="cls_052"> Leave Allocation and Application</span>
      </div>
      <div class="cls_054 bullet">
        <span class="cls_054 bullet dotter orionTeal--text">•</span
        ><span class="cls_052"> Employee Advance and Expense Claim</span>
      </div>
      <div class="cls_054 bullet">
        <span class="cls_054 bullet dotter orionTeal--text">•</span
        ><span class="cls_052"> Loan Application</span>
      </div>
      <div>
        <span class="cls_054 dotter orionTeal--text">•</span
        ><span class="cls_052"> Performance Appraisal</span>
      </div>
    </div>
    <div>
      <!-- <div> -->
      <!-- <img src="/projects/ogun/imgs/background28.jpg" width="100%" /> -->
      <!-- </div> -->
      <br />
      <div class="cls_012">
        <span class="super-subtitle orionTeal--text mt-10 mb-10 cls_012"
          >HR and Payroll - Job Application</span
        >
      </div>
      <div class="cls_018 bullet">
        <span class="cls_018 bullet dotter orionTeal--text">•</span
        ><span class="cls_014">
          You can maintain a list of People who have applied for a Job
          Opening.</span
        >
      </div>
      <div class="cls_018 bullet">
        <span class="cls_018 bullet dotter orionTeal--text">•</span
        ><span class="cls_014">
          You can link Job Application with an Email account.</span
        >
      </div>
      <div class="cls_018 bullet">
        <span class="cls_018 bullet dotter orionTeal--text">•</span
        ><span class="cls_014">
          Suppose you link Job Application with an email job@example.com
          OGUN</span
        >
      </div>
      <div class="cls_014 bullet">
        <span class="cls_014 bullet"
          >shall create a New Job Applicant against each email received on the
          mailbox.</span
        >
      </div>
    </div>
    <div>
      <!-- <div> -->
      <!-- <img src="/projects/ogun/imgs/background29.jpg" width="100%" /> -->
      <!-- </div> -->
      <br />
      <div class="cls_012">
        <span class="super-subtitle orionTeal--text mt-10 mb-10 cls_012"
          >HR and Payroll - Holidays List</span
        >
      </div>
      <div class="cls_018 bullet">
        <span class="cls_018 bullet dotter orionTeal--text">•</span
        ><span class="cls_014">
          day List is a list which contains the dates of holidays.</span
        >
      </div>
      <div class="cls_018 bullet">
        <span class="cls_018 bullet dotter orionTeal--text">•</span
        ><span class="cls_014">
          Most organizations have a standard Holiday-List for their
          employees.</span
        >
      </div>
      <div class="cls_018 bullet">
        <span class="cls_018 bullet dotter orionTeal--text">•</span
        ><span class="cls_014">
          Some even have different holiday lists based on the different
          locations or</span
        >
      </div>
      <div class="cls_014 bullet">
        <span class="cls_014 bullet">departments.</span>
      </div>
    </div>
    <div>
      <!-- <div> -->
      <!-- <img src="/projects/ogun/imgs/background30.jpg" width="100%" /> -->
      <!-- </div> -->
      <br />
      <div class="cls_012">
        <span class="super-subtitle orionTeal--text mt-10 mb-10 cls_012"
          >HR and Payroll - Loan Type</span
        >
      </div>
      <div class="cls_018 bullet">
        <span class="cls_018 bullet dotter orionTeal--text">•</span
        ><span class="cls_014">
          This module enables companies which provides loans to define and
          manage</span
        >
      </div>
      <div class="cls_014 bullet">
        <span class="cls_014 bullet"
          >loans. Employees can request loans, which are then reviewed and
          approved.</span
        >
      </div>
      <div class="cls_018 bullet">
        <span class="cls_018 bullet dotter orionTeal--text">•</span
        ><span class="cls_014">
          For the approved loans, repayment schedule for the entire loan cycle
          can be</span
        >
      </div>
      <div class="cls_014 bullet">
        <span class="cls_014 bullet"
          >generated and automatic deduction from salary can also be set
          up.</span
        >
      </div>
    </div>
    <div>
      <!-- <div> -->
      <!-- <img src="/projects/ogun/imgs/background31.jpg" width="100%" /> -->
      <!-- </div> -->
      <br />
      <div id="assets" class="cls_012">
        <span class="super-subtitle orionTeal--text mt-10 mb-10 cls_012"
          >Asset Management</span
        >
      </div>
      <div class="cls_055 bullet">
        <span class="cls_055 bullet"
          >Fixed asset management and tracking with depreciation, asset
          allocation and movement tracking</span
        >
      </div>
      <div class="cls_056 bullet">
        <span class="cls_056 bullet dotter orionTeal--text">•</span
        ><span class="cls_055"> Asset</span>
      </div>
      <div class="cls_057 bullet">
        <span class="cls_057 bullet dotter orionTeal--text">•</span
        ><span class="cls_058">
          All the transactions related to an Asset like purchasing, sales,
          depreciation, scrapping, movement</span
        >
      </div>
      <div class="cls_058 bullet">
        <span class="cls_058 bullet"
          >or maintenance will be managed against the Asset master.</span
        >
      </div>
      <div class="cls_056 bullet">
        <span class="cls_056 bullet dotter orionTeal--text">•</span
        ><span class="cls_055"> Asset Maintenance</span>
      </div>
      <div class="cls_057 bullet">
        <span class="cls_057 bullet dotter orionTeal--text">•</span
        ><span class="cls_058">
          OGUN provides features to track the details of individual
          maintenance/calibration of various assets.</span
        >
      </div>
      <div class="cls_056 bullet">
        <span class="cls_056 bullet dotter orionTeal--text">•</span
        ><span class="cls_055"> Asset Movement</span>
      </div>
      <div class="cls_057 bullet">
        <span class="cls_057 bullet dotter orionTeal--text">•</span
        ><span class="cls_058">
          You can track the location of an asset or to whom it is issued or
          whenever it is moved from one</span
        >
      </div>
      <div class="cls_058 bullet">
        <span class="cls_058 bullet">location to another.</span>
      </div>
    </div>
    <div>
      <!-- <div> -->
      <!-- <img src="/projects/ogun/imgs/background32.jpg" width="100%" /> -->
      <!-- </div> -->
      <br />
      <div class="cls_012">
        <span class="super-subtitle orionTeal--text mt-10 mb-10 cls_012"
          >Asset Management - Asset Transactions</span
        >
      </div>
      <div>
        <span class="cls_059 dotter orionTeal--text">•</span
        ><span class="cls_060"> Asset Value Adjustment</span>
      </div>
      <div class="cls_061 bullet">
        <span class="cls_061 bullet dotter orionTeal--text">•</span
        ><span class="cls_062">
          In case of fixed asset management, sometimes the value of an asset
          needs some</span
        >
      </div>
      <div class="cls_062 bullet">
        <span class="cls_062 bullet"
          >adjustment, this can be managed within OGUN.</span
        >
      </div>
      <div class="cls_059 bullet">
        <span class="cls_059 bullet dotter orionTeal--text">•</span
        ><span class="cls_060"> Purchasing an Asset</span>
      </div>
      <div class="cls_061 bullet">
        <span class="cls_061 bullet dotter orionTeal--text">•</span
        ><span class="cls_062">
          You can follow the default purchase cycle after ensuring the the
          appropriate asset</span
        >
      </div>
      <div class="cls_062 bullet">
        <span class="cls_062 bullet">category exists.</span>
      </div>
      <div class="cls_059 bullet">
        <span class="cls_059 bullet dotter orionTeal--text">•</span
        ><span class="cls_060"> Selling an Asset</span>
      </div>
      <div class="cls_061 bullet">
        <span class="cls_061 bullet dotter orionTeal--text">•</span
        ><span class="cls_062">
          You can sell an asset and even make all the necessary documents lile a
          Sales</span
        >
      </div>
      <div class="cls_062 bullet">
        <span class="cls_062 bullet">Invoice for it.</span>
      </div>
    </div>
    <div>
      <!-- <div> -->
      <!-- <img src="/projects/ogun/imgs/background33.jpg" width="100%" /> -->
      <!-- </div> -->
      <br />
      <div class="cls_012">
        <span class="super-subtitle orionTeal--text mt-10 mb-10 cls_012"
          >Asset Management - Discarding Assets</span
        >
      </div>
      <div class="cls_063 bullet">
        <span class="cls_063 bullet dotter orionTeal--text">•</span
        ><span class="cls_015"> Asset Depreciation</span>
      </div>
      <div class="cls_018 bullet">
        <span class="cls_018 bullet dotter orionTeal--text">•</span
        ><span class="cls_014">
          The system automatically creates a schedule for depreciation based
          on</span
        >
      </div>
      <div class="cls_014 bullet">
        <span class="cls_014 bullet"
          >depreciation method and other related inputs in the Asset
          record.</span
        >
      </div>
      <div class="cls_063 bullet">
        <span class="cls_063 bullet dotter orionTeal--text">•</span
        ><span class="cls_015"> Scrapping an Asset</span>
      </div>
      <div class="cls_018 bullet">
        <span class="cls_018 bullet dotter orionTeal--text">•</span
        ><span class="cls_014">
          When an asset is no longer usable, you can scrap an asset with the
          click of</span
        >
      </div>
      <div class="cls_014 bullet">
        <span class="cls_014 bullet">a button in the Asset record.</span>
      </div>
    </div>
    <div>
      <!-- <div> -->
      <!-- <img src="/projects/ogun/imgs/background34.jpg" width="100%" /> -->
      <!-- </div> -->
      <br />
      <div>
        <span class="cls_010 super-title orionAmber--text">Expectations</span>
      </div>
      <div class="cls_012 bullet">
        <span class="cls_012 bullet">OGUN grantees you:</span>
      </div>
      <div class="cls_064 bullet">
        <span class="cls_064 bullet dotter orionTeal--text">•</span
        ><span class="cls_065"> Track all Invoices and Payments.</span>
      </div>
      <div class="cls_064 bullet">
        <span class="cls_064 bullet dotter orionTeal--text">•</span
        ><span class="cls_065">
          Know what quantity of which product is available in stock.</span
        >
      </div>
      <div class="cls_064 bullet">
        <span class="cls_064 bullet dotter orionTeal--text">•</span
        ><span class="cls_065">
          Identify and track your key performance indicators (KPI's).</span
        >
      </div>
      <div class="cls_064 bullet">
        <span class="cls_064 bullet dotter orionTeal--text">•</span
        ><span class="cls_065"> Identify open customer queries.</span>
      </div>
      <div class="cls_064 bullet">
        <span class="cls_064 bullet dotter orionTeal--text">•</span
        ><span class="cls_065"> Manage payroll.</span>
      </div>
      <div class="cls_064 bullet">
        <span class="cls_064 bullet dotter orionTeal--text">•</span
        ><span class="cls_065"> Assign tasks and follow up on them.</span>
      </div>
      <div class="cls_064 bullet">
        <span class="cls_064 bullet dotter orionTeal--text">•</span
        ><span class="cls_065">
          Maintain a database of all your customers, suppliers and their
          contacts.</span
        >
      </div>
      <div class="cls_064 bullet">
        <span class="cls_064 bullet dotter orionTeal--text">•</span
        ><span class="cls_065"> Prepare quotes.</span>
      </div>
      <div class="cls_064 bullet">
        <span class="cls_064 bullet dotter orionTeal--text">•</span
        ><span class="cls_065"> Tracking your budgets and spending</span>
      </div>
      <div class="cls_064 bullet">
        <span class="cls_064 bullet dotter orionTeal--text">•</span
        ><span class="cls_065">
          Determine effective selling price based on the actual raw material,
          machinery and effort cost.</span
        >
      </div>
      <div class="cls_064 bullet">
        <span class="cls_064 bullet dotter orionTeal--text">•</span
        ><span class="cls_065"> Get reminders on maintenance schedules.</span>
      </div>
      <div class="cls_064 bullet">
        <span class="cls_064 bullet dotter orionTeal--text">•</span
        ><span class="cls_065"> Publish your website</span>
      </div>
    </div>
    <v-divider />
    <h1 class="orionAmber--text text-center mt-5 mb-5">Thank You.</h1>
    <v-row justify="center" class="logo-holder">
      <v-col cols="12" :xs="12" :lg="4" :md="6">
        <v-img
          src="/imgs/projects/ogun-white.png"
          contain
          max-width="400px"
          class="animate__animated animate__fadeInLeft delay"
        />
      </v-col>
      <v-col cols="12" :xs="12">
        <div class="text-center animate__animated animate__fadeInRight delay">
          <span class="logo-sub-2">Brought to you by</span
          ><span class="logo-sub-founder"> </span
          ><span class="font-weight-bold logo-sub-founder">ORION</span>
        </div>
      </v-col>
    </v-row>
    <v-divider class="mb-10" />
  </div>
</template>

<script>
export default {
  name: 'OgunIndex',
  layout: 'orion',
  data() {
    return {}
  },
  head: {
    title: 'OGUN',
    meta: [
      { property: 'og:title', hid: 'og:title', content: 'OGUN' },
      {
        property: 'og:description',
        hid: 'og:description',
        content: 'Manufacturing ERP System.',
      },
      {
        property: 'og:image',
        content: 'https://orionstelars.com/imgs/projects/ogun.png',
      },
      {
        hid: 'og:site_name',
        property: 'og:site_name',
        name: 'og:site_name',
        content: 'Orion Developments',
      },
    ],
  },
}
</script>

<style lang="css" scoped>
span.cls_002 {
  font-family: sans-serif;
  font-weight: bold;
  font-style: italic;
  text-decoration: none;
}
div.cls_002 {
  font-family: sans-serif;
  font-weight: bold;
  font-style: italic;
  text-decoration: none;
}
span.cls_003 {
  font-family: sans-serif;
  font-weight: bold;
  font-style: normal;
  text-decoration: none;
}
div.cls_003 {
  font-family: sans-serif;
  font-weight: bold;
  font-style: normal;
  text-decoration: none;
}
span.cls_007 {
  font-family: sans-serif;
  font-weight: bold;
  font-style: italic;
  text-decoration: none;
}
div.cls_007 {
  font-family: sans-serif;
  font-weight: bold;
  font-style: italic;
  text-decoration: none;
}
span.cls_008 {
  font-family: sans-serif;
  font-weight: bold;
  font-style: normal;
  text-decoration: none;
}
div.cls_008 {
  font-family: sans-serif;
  font-weight: bold;
  font-style: normal;
  text-decoration: none;
}
span.cls_009 {
  font-family: sans-serif;
  font-weight: bold;
  font-style: normal;
  text-decoration: none;
}
div.cls_009 {
  font-family: sans-serif;
  font-weight: bold;
  font-style: normal;
  text-decoration: none;
}
span.cls_004 {
  font-family: sans-serif;
  font-weight: normal;
  font-style: normal;
  text-decoration: none;
}
div.cls_004 {
  font-family: sans-serif;
  font-weight: normal;
  font-style: normal;
  text-decoration: none;
}
span.cls_005 {
  font-family: sans-serif;
  font-weight: bold;
  font-style: normal;
  text-decoration: none;
}
div.cls_005 {
  font-family: sans-serif;
  font-weight: bold;
  font-style: normal;
  text-decoration: none;
}
span.cls_006 {
  font-family: sans-serif;
  font-weight: bold;
  font-style: normal;
  text-decoration: none;
}
div.cls_006 {
  font-family: sans-serif;
  font-weight: bold;
  font-style: normal;
  text-decoration: none;
}
span.cls_010 {
  font-family: sans-serif;
  font-weight: bold;
  font-style: normal;
  text-decoration: none;
}
div.cls_010 {
  font-family: sans-serif;
  font-weight: bold;
  font-style: normal;
  text-decoration: none;
}
span.cls_011 {
  font-family: sans-serif;
  font-weight: bold;
  font-style: normal;
  text-decoration: none;
}
div.cls_011 {
  font-family: sans-serif;
  font-weight: bold;
  font-style: normal;
  text-decoration: none;
}
span.cls_012 {
  font-family: sans-serif;
  font-weight: bold;
  font-style: normal;
  text-decoration: none;
}
div.cls_012 {
  font-family: sans-serif;
  font-weight: bold;
  font-style: normal;
  text-decoration: none;
}
span.cls_013 {
  font-family: sans-serif;
  font-weight: normal;
  font-style: normal;
  text-decoration: none;
}
div.cls_013 {
  font-family: sans-serif;
  font-weight: normal;
  font-style: normal;
  text-decoration: none;
}
span.cls_014 {
  font-family: sans-serif;
  font-weight: normal;
  font-style: normal;
  text-decoration: none;
}
div.cls_014 {
  font-family: sans-serif;
  font-weight: normal;
  font-style: normal;
  text-decoration: none;
}
span.cls_015 {
  font-family: sans-serif;
  font-weight: bold;
  font-style: normal;
  text-decoration: none;
}
div.cls_015 {
  font-family: sans-serif;
  font-weight: bold;
  font-style: normal;
  text-decoration: none;
}
span.cls_016 {
  font-family: sans-serif;
  font-weight: normal;
  font-style: normal;
  text-decoration: none;
}
div.cls_016 {
  font-family: sans-serif;
  font-weight: normal;
  font-style: normal;
  text-decoration: none;
}
span.cls_017 {
  font-family: sans-serif;
  font-weight: bold;
  font-style: normal;
  text-decoration: none;
}
div.cls_017 {
  font-family: sans-serif;
  font-weight: bold;
  font-style: normal;
  text-decoration: none;
}
span.cls_018 {
  font-family: sans-serif;
  font-weight: normal;
  font-style: normal;
  text-decoration: none;
}
div.cls_018 {
  font-family: sans-serif;
  font-weight: normal;
  font-style: normal;
  text-decoration: none;
}
span.cls_019 {
  font-family: sans-serif;
  font-weight: normal;
  font-style: normal;
  text-decoration: none;
}
div.cls_019 {
  font-family: sans-serif;
  font-weight: normal;
  font-style: normal;
  text-decoration: none;
}
span.cls_020 {
  font-family: sans-serif;
  font-weight: normal;
  font-style: normal;
  text-decoration: none;
}
div.cls_020 {
  font-family: sans-serif;
  font-weight: normal;
  font-style: normal;
  text-decoration: none;
}
span.cls_021 {
  font-family: sans-serif;
  font-weight: normal;
  font-style: normal;
  text-decoration: none;
}
div.cls_021 {
  font-family: sans-serif;
  font-weight: normal;
  font-style: normal;
  text-decoration: none;
}
span.cls_022 {
  font-family: sans-serif;
  font-weight: normal;
  font-style: normal;
  text-decoration: none;
}
div.cls_022 {
  font-family: sans-serif;
  font-weight: normal;
  font-style: normal;
  text-decoration: none;
}
span.cls_023 {
  font-family: sans-serif;
  font-weight: normal;
  font-style: normal;
  text-decoration: none;
}
div.cls_023 {
  font-family: sans-serif;
  font-weight: normal;
  font-style: normal;
  text-decoration: none;
}
span.cls_024 {
  font-family: sans-serif;
  font-weight: normal;
  font-style: normal;
  text-decoration: none;
}
div.cls_024 {
  font-family: sans-serif;
  font-weight: normal;
  font-style: normal;
  text-decoration: none;
}
span.cls_025 {
  font-family: sans-serif;
  font-weight: normal;
  font-style: normal;
  text-decoration: none;
}
div.cls_025 {
  font-family: sans-serif;
  font-weight: normal;
  font-style: normal;
  text-decoration: none;
}
span.cls_026 {
  font-family: sans-serif;
  font-weight: bold;
  font-style: italic;
  text-decoration: none;
}
div.cls_026 {
  font-family: sans-serif;
  font-weight: bold;
  font-style: italic;
  text-decoration: none;
}
span.cls_027 {
  font-family: sans-serif;
  font-weight: bold;
  font-style: normal;
  text-decoration: none;
}
div.cls_027 {
  font-family: sans-serif;
  font-weight: bold;
  font-style: normal;
  text-decoration: none;
}
span.cls_028 {
  font-family: sans-serif;
  font-weight: bold;
  font-style: normal;
  text-decoration: none;
}
div.cls_028 {
  font-family: sans-serif;
  font-weight: bold;
  font-style: normal;
  text-decoration: none;
}
span.cls_029 {
  font-family: sans-serif;
  font-weight: bold;
  font-style: normal;
  text-decoration: none;
}
div.cls_029 {
  font-family: sans-serif;
  font-weight: bold;
  font-style: normal;
  text-decoration: none;
}
span.cls_030 {
  font-family: sans-serif;
  font-weight: normal;
  font-style: normal;
  text-decoration: none;
}
div.cls_030 {
  font-family: sans-serif;
  font-weight: normal;
  font-style: normal;
  text-decoration: none;
}
span.cls_031 {
  font-family: sans-serif;
  font-weight: normal;
  font-style: normal;
  text-decoration: none;
}
div.cls_031 {
  font-family: sans-serif;
  font-weight: normal;
  font-style: normal;
  text-decoration: none;
}
span.cls_032 {
  font-family: sans-serif;
  font-weight: bold;
  font-style: normal;
  text-decoration: none;
}
div.cls_032 {
  font-family: sans-serif;
  font-weight: bold;
  font-style: normal;
  text-decoration: none;
}
span.cls_033 {
  font-family: sans-serif;
  font-weight: bold;
  font-style: normal;
  text-decoration: none;
}
div.cls_033 {
  font-family: sans-serif;
  font-weight: bold;
  font-style: normal;
  text-decoration: none;
}
span.cls_034 {
  font-family: sans-serif;
  font-weight: normal;
  font-style: normal;
  text-decoration: none;
}
div.cls_034 {
  font-family: sans-serif;
  font-weight: normal;
  font-style: normal;
  text-decoration: none;
}
span.cls_035 {
  font-family: sans-serif;
  font-weight: normal;
  font-style: normal;
  text-decoration: none;
}
div.cls_035 {
  font-family: sans-serif;
  font-weight: normal;
  font-style: normal;
  text-decoration: none;
}
span.cls_036 {
  font-family: sans-serif;
  font-weight: bold;
  font-style: normal;
  text-decoration: none;
}
div.cls_036 {
  font-family: sans-serif;
  font-weight: bold;
  font-style: normal;
  text-decoration: none;
}
span.cls_037 {
  font-family: sans-serif;
  font-weight: bold;
  font-style: normal;
  text-decoration: none;
}
div.cls_037 {
  font-family: sans-serif;
  font-weight: bold;
  font-style: normal;
  text-decoration: none;
}
span.cls_038 {
  font-family: sans-serif;
  font-weight: normal;
  font-style: normal;
  text-decoration: none;
}
div.cls_038 {
  font-family: sans-serif;
  font-weight: normal;
  font-style: normal;
  text-decoration: none;
}
span.cls_039 {
  font-family: sans-serif;
  font-weight: normal;
  font-style: normal;
  text-decoration: none;
}
div.cls_039 {
  font-family: sans-serif;
  font-weight: normal;
  font-style: normal;
  text-decoration: none;
}
span.cls_040 {
  font-family: sans-serif;
  font-weight: bold;
  font-style: normal;
  text-decoration: none;
}
div.cls_040 {
  font-family: sans-serif;
  font-weight: bold;
  font-style: normal;
  text-decoration: none;
}
span.cls_041 {
  font-family: sans-serif;
  font-weight: bold;
  font-style: normal;
  text-decoration: none;
}
div.cls_041 {
  font-family: sans-serif;
  font-weight: bold;
  font-style: normal;
  text-decoration: none;
}
span.cls_042 {
  font-family: sans-serif;
  font-weight: normal;
  font-style: normal;
  text-decoration: none;
}
div.cls_042 {
  font-family: sans-serif;
  font-weight: normal;
  font-style: normal;
  text-decoration: none;
}
span.cls_043 {
  font-family: sans-serif;
  font-weight: normal;
  font-style: normal;
  text-decoration: none;
}
div.cls_043 {
  font-family: sans-serif;
  font-weight: normal;
  font-style: normal;
  text-decoration: none;
}
span.cls_044 {
  font-family: sans-serif;
  font-weight: bold;
  font-style: normal;
  text-decoration: none;
}
div.cls_044 {
  font-family: sans-serif;
  font-weight: bold;
  font-style: normal;
  text-decoration: none;
}
span.cls_045 {
  font-family: sans-serif;
  font-weight: bold;
  font-style: normal;
  text-decoration: none;
}
div.cls_045 {
  font-family: sans-serif;
  font-weight: bold;
  font-style: normal;
  text-decoration: none;
}
span.cls_046 {
  font-family: sans-serif;
  font-weight: normal;
  font-style: normal;
  text-decoration: none;
}
div.cls_046 {
  font-family: sans-serif;
  font-weight: normal;
  font-style: normal;
  text-decoration: none;
}
span.cls_047 {
  font-family: sans-serif;
  font-weight: normal;
  font-style: normal;
  text-decoration: none;
}
div.cls_047 {
  font-family: sans-serif;
  font-weight: normal;
  font-style: normal;
  text-decoration: none;
}
span.cls_048 {
  font-family: sans-serif;
  font-weight: bold;
  font-style: normal;
  text-decoration: none;
}
div.cls_048 {
  font-family: sans-serif;
  font-weight: bold;
  font-style: normal;
  text-decoration: none;
}
span.cls_049 {
  font-family: sans-serif;
  font-weight: bold;
  font-style: normal;
  text-decoration: none;
}
div.cls_049 {
  font-family: sans-serif;
  font-weight: bold;
  font-style: normal;
  text-decoration: none;
}
span.cls_050 {
  font-family: sans-serif;
  font-weight: normal;
  font-style: normal;
  text-decoration: none;
}
div.cls_050 {
  font-family: sans-serif;
  font-weight: normal;
  font-style: normal;
  text-decoration: none;
}
span.cls_051 {
  font-family: sans-serif;
  font-weight: normal;
  font-style: normal;
  text-decoration: none;
}
div.cls_051 {
  font-family: sans-serif;
  font-weight: normal;
  font-style: normal;
  text-decoration: none;
}
span.cls_052 {
  font-family: sans-serif;
  font-weight: normal;
  font-style: normal;
  text-decoration: none;
}
div.cls_052 {
  font-family: sans-serif;
  font-weight: normal;
  font-style: normal;
  text-decoration: none;
}
span.cls_053 {
  font-family: sans-serif;
  font-weight: bold;
  font-style: normal;
  text-decoration: none;
}
div.cls_053 {
  font-family: sans-serif;
  font-weight: bold;
  font-style: normal;
  text-decoration: none;
}
span.cls_054 {
  font-family: sans-serif;
  font-weight: normal;
  font-style: normal;
  text-decoration: none;
}
div.cls_054 {
  font-family: sans-serif;
  font-weight: normal;
  font-style: normal;
  text-decoration: none;
}
span.cls_055 {
  font-family: sans-serif;
  font-weight: bold;
  font-style: normal;
  text-decoration: none;
}
div.cls_055 {
  font-family: sans-serif;
  font-weight: bold;
  font-style: normal;
  text-decoration: none;
}
span.cls_056 {
  font-family: sans-serif;
  font-weight: bold;
  font-style: normal;
  text-decoration: none;
}
div.cls_056 {
  font-family: sans-serif;
  font-weight: bold;
  font-style: normal;
  text-decoration: none;
}
span.cls_057 {
  font-family: sans-serif;
  font-weight: normal;
  font-style: normal;
  text-decoration: none;
}
div.cls_057 {
  font-family: sans-serif;
  font-weight: normal;
  font-style: normal;
  text-decoration: none;
}
span.cls_058 {
  font-family: sans-serif;
  font-weight: normal;
  font-style: normal;
  text-decoration: none;
}
div.cls_058 {
  font-family: sans-serif;
  font-weight: normal;
  font-style: normal;
  text-decoration: none;
}
span.cls_059 {
  font-family: sans-serif;
  font-weight: bold;
  font-style: normal;
  text-decoration: none;
}
div.cls_059 {
  font-family: sans-serif;
  font-weight: bold;
  font-style: normal;
  text-decoration: none;
}
span.cls_060 {
  font-family: sans-serif;
  font-weight: bold;
  font-style: normal;
  text-decoration: none;
}
div.cls_060 {
  font-family: sans-serif;
  font-weight: bold;
  font-style: normal;
  text-decoration: none;
}
span.cls_061 {
  font-family: sans-serif;
  font-weight: normal;
  font-style: normal;
  text-decoration: none;
}
div.cls_061 {
  font-family: sans-serif;
  font-weight: normal;
  font-style: normal;
  text-decoration: none;
}
span.cls_062 {
  font-family: sans-serif;
  font-weight: normal;
  font-style: normal;
  text-decoration: none;
}
div.cls_062 {
  font-family: sans-serif;
  font-weight: normal;
  font-style: normal;
  text-decoration: none;
}
span.cls_063 {
  font-family: sans-serif;
  font-weight: bold;
  font-style: normal;
  text-decoration: none;
}
div.cls_063 {
  font-family: sans-serif;
  font-weight: bold;
  font-style: normal;
  text-decoration: none;
}
span.cls_064 {
  font-family: sans-serif;
  font-weight: normal;
  font-style: normal;
  text-decoration: none;
}
div.cls_064 {
  font-family: sans-serif;
  font-weight: normal;
  font-style: normal;
  text-decoration: none;
}
span.cls_065 {
  font-family: sans-serif;
  font-weight: normal;
  font-style: normal;
  text-decoration: none;
}
div.cls_065 {
  font-family: sans-serif;
  font-weight: normal;
  font-style: normal;
  text-decoration: none;
}
.bullet {
  font-size: 24px !important;
}
.title {
  font-size: 48px !important;
}
.subtitle {
  font-size: 32px;
}
.super-title {
  font-size: 52px;
  margin-top: 30px !important;
}
.super-subtitle {
  font-size: 34px;
  margin-bottom: 25px !important;
}
.dotter {
  font-size: 26px !important;
}
.logo {
  font-size: 74px;
}
.logo-sub {
  font-size: 50px;
}
.logo-sub-2 {
  font-size: 25px;
}
.logo-sub-founder {
  font-size: 25px;
  margin-left: 2px;
}
.logo-holder {
  min-height: 200px;
  transition: height 0.5s ease;
}
.delay {
  animation-delay: 1.5s;
}
.quick-nav {
  text-decoration: none;
  font-weight: bold;
}
</style>
